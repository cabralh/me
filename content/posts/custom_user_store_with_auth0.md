+++
title = "Using Auth0 with a custom user store"
author = ["mrprofessor"]
date = 2022-03-28
tags = ["auth", "python"]
draft = false
+++

<div class="ox-hugo-toc toc">

<div class="heading">Table of Contents</div>

- [The problem](#the-problem)
- [Ground work](#ground-work)
    - [Set up the Database](#set-up-the-database)
    - [Auth0 setup](#auth0-setup)
- [Auth0 actions configuration](#auth0-actions-configuration)

</div>
<!--endtoc-->

Auth0 is an identity management solution for Web, Mobile, and IoT devices. It supports almost all types of authentication mechanisms and eases the complexity of both authentication and authorization. However, like everything else it has it's limits. Particularly there is one limit I have recently faced, and this post is nothing but a POC to the solution.


## The problem {#the-problem}

Auth0 has it's own user store; however, it requires that `email` address must be unique for each user(per connection). In other words, Auth0 doesn't support unique username based user database, where email may not be unique. This `one user per email` is a widely popular pattern, since the Internet chose it for us.


## Ground work {#ground-work}

So in this post, we will setup a PostgreSQL database with some user data. Then we will connect the Auth0 to our database and test some usual authentication stuff.


### Set up the Database {#set-up-the-database}

I have used [heroku free tier](https://elements.heroku.com/addons/heroku-postgresql) plans to create a Postgres database. Let's use `psql` to connect the remote database.

```sh
psql -h <host> <port> -d <db_name> -U <user>
```

Then I have created a table named `user` and added some data in it.

```sql
-- Add uuid extention
CREATE EXTENSION IF NOT EXISTS "uuid-ossp";

-- Create an user table with minimal structure
CREATE TABLE "user" (
  id uuid DEFAULT uuid_generate_v4 () NOT NULL,
  name VARCHAR(100),
  login VARCHAR(150) UNIQUE,
  PRIMARY KEY(id)
)

-- Seed the table with some data
INSERT INTO "user" ("name", "login")
VALUES ('Rick Sanchez', 'rick_sanchez'),
       ('Morty Smith', 'morty_smith'),
       ('BirdPerson', 'bird_persion');
```

And we got some users in.

```shell
> select * from "user";

                  id                  |     name     |    login
--------------------------------------+--------------+--------------
 b49daf2a-af3b-4d91-966f-92159c726601 | Rick Sanchez | rick_sanchez
 01906f5b-7be3-4ce8-87c0-418e7e20d610 | Morty Smith  | morty_smith
 b0e92da5-5b8e-41ca-9dad-037c29c1f695 | BirdPerson   | bird_persion
(3 rows)
```


### Auth0 setup {#auth0-setup}

I have created an tenant in Auth0 and added a custom database connection. Auth0 has [documented](https://auth0.com/docs/authenticate/database-connections/custom-db/create-db-connection) the step by step process to do so.

<div class="post-image">
  <img src="/images/posts/custom_user_store_with_auth0/auth0_custom_db_settings.png" loading="lazy"/>
  <span class="img-description"> Custom Database settings </span>
</div>

Then we need to setup an application with our custom database connection. To create a new application we need to navigate to `Auth0 Dashboard > Applications > Applications`.
Auth0 has a detailed [documentation](https://auth0.com/docs/get-started/applications) explaining various aspects of registering an application.

In the application setting we need to provide an callback URL(address where you will be redirected after a successful authentication).

<div class="post-image">
  <img src="/images/posts/custom_user_store_with_auth0/auth0_callback_url.png" loading="lazy"/>
  <span class="img-description"> Auth0 application callback URL </span>
</div>

Also we need to make sure that the custom database connection is enabled for the application

<div class="post-image">
  <img src="/images/posts/custom_user_store_with_auth0/auth0_app_connections.png" loading="lazy"/>
  <span class="img-description"> Auth0 application connections </span>
</div>

We can also customize our login page in `Auth0 Dashboard > Branding`, and I have customized the logo and colors. Now we can use this format to got to the landing page.

```sh
[Auth0 application URL]/authorize?
  response_type=token&
  client_id=[CLIENT_ID]&
  connection=[CONNECTION_NAME]&
  redirect_uri=[REDIRECT_URI]

example:

https://custom-user-store.jp.auth0.com/authorize?
  response_type=token&
  client_id=GgdwqkegdUxo1yZT5GA9fclient_id&
  connection=custom-user-store&
  redirect_uri=https://www.rudra.dev/keyboards
```

And we get the Auth0 login page.

<div class="post-image">
  <img src="/images/posts/custom_user_store_with_auth0/auth0_login_page.png" loading="lazy"/>
  <span class="img-description"> Auth0 login page </span>
</div>


## Auth0 actions configuration {#auth0-actions-configuration}

Now that we got everything set up, we can work on the Auth0 actions(login, sign up, password change etc). Auth0 allows users to create their custom scripts to autheticate with their database, but the script must return an unique `user_id`. The scripts must be written in Javascript, which will run as anonymous functions on Auth0's Node.js platform.
