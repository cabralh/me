+++
title = "How Additive Manufacturing is Advancing Product Development"
author = ["henrycabral"]
date = 2022-03-01
tags = ["design", "product development", "product design", "industrial design", "business"]
draft = false
+++

<div class="ox-hugo-toc toc">
<div></div>

<div class="heading">Table of Contents</div>

- [The industrial shift towards in-house prototyping and design](#the-industrial-shift-towards-in-house-prototyping-and-design)
- [What is Additive Manufacturing (AM)?](#what-is-additive-manufacturing-am)
- [Modern AM Technologies](#modern-am-technologies)
  - [Fused Deposition Modeling/Fused Filament Fabrication (FDM/FFF)⁵](#fused-deposition-modelingfused-filament-fabrication-fdmfff)
  - [Stereolithography (SLA)](#stereolithography-sla)
  - [Masked Stereolithography (MSLA)](#masked-stereolithography-msla)
  - [Digital Light Processing (DLP)](#digital-light-processing-dlp)
  - [Selective Laser Sintering (SLS)](#selective-laser-sintering-sls)
  - [Direct Metal Laser Sintering (DMLS)](#direct-metal-laser-sintering-dmls)
  - [Selective Laser Melting (SLM)](#selective-laser-melting-slm)
- [The current status of AM](#the-current-status-of-am)
  - [Product development using AM](#product-development-using-am)
  - [Industry outlook of AM](#industry-outlook-of-am)
  - [Innovative companies in AM](#innovative-companies-in-am)
    - [Formlabs](#formlabs)
    - [Aprecia Pharmaceuticals](#aprecia-pharmaceuticals)
    - [Relativity Space](#relativity-space)
- [The Future of AM](#the-future-of-am)
  - [Future technologies](#future-technologies)
  - [Dual Extrusion](#dual-extrusion)
  - [Continual Expansion of AM into various industries to support rapid prototyping and product development](#continual-expansion-of-am-into-various-industries-to-support-rapid-prototyping-and-product-development)
  - [New material selection \& properties](#new-material-selection--properties)
  - [Composite 3D printing](#composite-3d-printing)
  - [AI-enhanced additive manufacturing](#ai-enhanced-additive-manufacturing)
  - [Metal 3D printing advancement](#metal-3d-printing-advancement)
- [Challenges](#challenges)
- [Final Thoughts](#final-thoughts)
- [References](#references)

</div>
<!--endtoc-->

## The industrial shift towards in-house prototyping and design

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*F_L3SX8XhaMN4fWs" alt="Image of 3d printed rocket by Relativity Space.
  3D Printed Rocket by Startup Company, Relativity Space." title="Image of 3d printed rocket by Relativity Space.
  3D Printed Rocket by Startup Company, Relativity Space." />
  Image of 3d printed rocket by Relativity Space.
  3D Printed Rocket by Startup Company, Relativity Space.<sup>24</sup>
</div>

The adaption of 3D Printing has allowed for innovation in manufacturing that renders several benefits that I will get to in this article.

Additive manufacturing has made incredible strides in the past decade, paving the way for rapid prototype development in [various industries](https://markforged.com/resources/blog/five-industries-utilizing-3d-printing). This movement has also given birth to new companies that utilize this technology to create new products.

## What is Additive Manufacturing (AM)?

Manufacturing is the creation of physical parts or assemblies. Traditional manufacturing has existed since the Industrial Age.

Formlabs defines subtractive manufacturing as:

> An umbrella term for various controlled machining and material removal processes that start with solid blocks, bars, rods of plastic, metal, or other materials that are shaped by removing material through cutting, boring, drilling, and grinding.¹

Traditional (subtractive) manufacturing involves injection molding, CNC machining, laser cutting, etc.¹ To be able to put together a product requires timing, design time, material source, cost, validated processes, technicians, operators, managers, etc.

Subtractive means you take raw material and deduce its structure to create a part or component.

What about the opposite? Adding material instead of removing it?

*Enter AM.*

According to [General Electric](https://www.ge.com/additive/additive-manufacturing):

> Additive manufacturing (AM), also known as 3D Printing, is a transformative approach to industrial production that enables the creation of lighter, stronger parts and systems.²⁵

Another word that is synonymous with AM is 3D Printing.

This technology enables parts to be produced in intricate and complex geometries deemed difficult for traditional manufacturing methods. Coupled with an extensive array of material selection, additive manufacturing allows components to be created with one or more material properties depending on the use case.

For example, using Fused Deposition Modeling (FDM) or Fused Filament Fabrication (FFF) technology, the user can design a complex part that encompasses multiple kinds of filaments, tailoring the part with numerous functionalities and material characteristics.

Additive Manufacturing also tends to have:

*Lower upfront costs compared to traditional manufacturing techniques such as investment casting, sand casting, or metal injection molding.²*

Traditional manufacturing considers [the material price](https://www.3deo.co/strategy/costs-of-traditional-vs-additive-manufacturing/) while AM does not since it is roughly the same per part. This technology has also been around since the 19th century, during the Industrial Revolution.

Let’s jump into the origins of additive manufacturing, where it is today, and where it’s headed.

How AM got started
Additive manufacturing did not get started until the 1970s when Johannes F. Gottwald (Xerox Corp.) filed the invention of what was called the Liquid Metal Recorder.<sup>3</sup> This device “acted as a metal inkjet printer that allowed quick removal and reuse by remelting.”

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*s5qS9PVkSWUnmDD4" alt="Image of Liquid metal recorder patented on July 27, 1971." title="Image of Liquid metal recorder patented on July 27, 1971."/>
  Image of Liquid metal recorder patented on July 27, 1971.<sup>3</sup>
</div>

This design took electrically charged liquid metal injected it into space. Using magnetic deflection, the metal would impart, using current, itself onto a surface or “carrier” as listed in the patent.

As written in the patent:

> A first of the flux fields is induced about the ink (metal) stream by passing a current through it as it travels across the span between the nozzle from which it has been ejected to the carrier, and the second field is disposed about the first.

Electrically charged metal ink flows out of a nozzle through a span or space onto a carrier. “…[the ink] will flow at printing temperature but solidify as it contacts the carrier.

By providing an impervious or imperforate endless carrier, for example, of metal fabrication, a formed symbol may be removed therefrom to enable reuse of the carrier and metal salvage.”

Depositing metal onto a carrier or build surface allows for reuse of that surface. Looking at how all 3D printers work, the theory is pretty much the same.

You have a material imparter that deposits a material. It could be a roller that adds a layer of powder, a dosator that deposits powder, or an extruder that adds liquid filament onto a build surface.

From there, the material becomes a solid through cooling means or assisted via laser sintering.

Repeat this cycle several times, add different orientations of the impactor in space, and you have a 3D-printed part of a complex or straightforward shape built on a reusable build plate.

*This served as a foundation for additive manufacturing technologies today.*

Fast forward to today, modern 3D Printing is becoming an accessible technology used to design parts quickly, with incredible detail and intricate design patterns.

## Modern AM Technologies

Since the discovery of the liquid metal recorded, several additive manufacturing technologies have given birth, with more advancements made in the last decade.

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*_81cnIzQF3s6aH8_" alt="Additive Manufacturing Technologies Poster by 3D Hubs" title="Additive Manufacturing Technologies Poster by 3D Hubs"/>
  Additive Manufacturing Technologies, 3D Hubs <sup>4</sup>
</div>

For the purposes of this article, I will stick to the more mainstream technologies such as SLA/DLP, FDM/FFF, SLS, and DMLS/SLM.

### Fused Deposition Modeling/Fused Filament Fabrication (FDM/FFF)⁵

FDM-equipped printers incorporate a moving nozzle on a two-direction (typically X & Z if its Cartesian-based) axis ejects molten plastic onto a moveable platform (X & Y-axis).

Each line of plastic forms a pattern that’s deposited on the forum. This is referred to as a layer. The nozzle then repeats the process per layer, creating a printed part. FDM printers hold their material in a plastic spool that exists either on or beside the machine.

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*_zAW_Ney9r16dKdc" alt="Fused Filament Fabrication Diagram, 3D Hubs." title="Fused Filament Fabrication Diagram, 3D Hubs."/>
  Fused Filament Fabrication Diagram, 3D Hubs <sup>5</sup>
</div>

### Stereolithography (SLA)

SLA printers work in a similar layer-by-layer fashion. The difference arises in how the layers are built.

Instead of depositing plastic onto a moveable platform, the platform is submerged into a bath of resin material cured using an ultraviolet laser. As each layer is built and fixed, the platform moves upward to allow for the next layer space.

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*EJ2hO6NRtiXjXSnX" alt="Stereolithography Diagram by 3D Hubs." title="Stereolithography Diagram by 3D Hubs."/>
  Stereolithography Diagram, 3D Hubs <sup>5</sup>
</div>

### Masked Stereolithography (MSLA)

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*Jamoi-EF5-dck-r9" alt="Resin 3D Printing Technology by Matterhackers." title="Resin 3D Printing Technology by Matterhackers."/>
  Resin 3D Printing Technology by Matterhackers. <sup>7</sup>
</div>

Similar to SLA, MSLA uses a light source to cure. The significant difference is that an LCD screen with an LED cures each layer instead of a laser.

The LCD sits in front of the LED. MSLA technology uses the LCD/LED combination to cure certain portions of the layer depending on where light is blocked or allowed from the LCD screen.

### Digital Light Processing (DLP)

DLP is commonly used in resin 3D printing. Prusa, Formlabs, and Anycubic provide DLP/SLA printers for commercial use and hobbyist platforms.

DLP and SLA differ in the XY resolution, specifically how it is dictated. DLP printers use an LCD screen to cure individual profiles, whereas SLA depends on a laser.

The resolution on a DLP is determined by the LCD specification compared to the spot laser diameter within the Light Processing Unit (LPU) of an SLA printer.

The figure below best describes the differences between DLP and SLA technologies:

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*OekiGDoMMWv7ncsZ" alt="Stereolithography Comparison Diagram, Formlabs." title="Stereolithography Comparison Diagram, Formlabs."/>
  Stereolithography Comparison Diagram, Formlabs. <sup>6</sup>
</div>

### Selective Laser Sintering (SLS)

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*WQgYeTwEJ13AQiV0" alt="Selective Laser Sintering Diagram, Formlabs." title="Selective Laser Sintering Diagram, Formlabs."/>
  Selective Laser Sintering Diagram, Formlabs. <sup>8</sup>
</div>

Similar to SLA, [SLS](https://formlabs.com/blog/what-is-selective-laser-sintering/#:~:text=Selective) incorporates a laser to not cure but actually sinter or forges powdered material together into a solid structure.

> SLS 3D printing has been a popular choice for engineers and manufacturers. Low cost per part, high productivity, and established materials make the technology ideal for a range of applications from [rapid prototyping](https://formlabs.com/blog/ultimate-guide-to-rapid-prototyping/) to small-batch, bridge, or custom [manufacturing](https://formlabs.com/industries/manufacturing/).⁸

Factors discussed above, such as low cost and custom manufacturing, make SLS an attractive option for rapid prototyping. Continuous on-demand Printing will continue to challenge traditional manufacturing standards as these technologies become more affordable and accessible.

### Direct Metal Laser Sintering (DMLS)

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*LNzMnNmTeJ-X7W1P" alt="Metal 3D Printing — Laser Sintering." title="Metal 3D Printing — Laser Sintering."/>
  Metal 3D Printing  —  Laser Sintering. <sup>9</sup>
</div>

Also known as SLS, DMLS is the metal equivalent of laser sintering. This method is similar to SLM, which I will cover briefly in the next section. Sintering is essentially a welding technique.

The metal powder molecules are sintered and not melted together during Printing. This allows additional materials to be combined together, tailoring your assembly or components to various material characteristics.

### Selective Laser Melting (SLM)

<div class="post-image">
  <img src="https://miro.medium.com/max/1100/0*DaZS-JdeKRCJcWk4" alt="Selective Laser Melting." title="Selective Laser Melting."/>
  Selective Laser Melting. <sup>10</sup>
</div>

The printing process compared to DMLS is relatively the same. A powder bed is filled with metal powder. Adjacent to the bed is an empty build chamber. Per layer, the recoater arm applies powder to the empty build chamber at a certain distance in height.

Once a layer of powder is used, a laser melts the powder then solidifies per layer. The next layer of fresh powder is applied to the build chamber as the chamber moves down in height in increments. Rinse and repeat until the part is finished.

The main difference between SLM and DMLS is that the metal molecules are melted into a liquid form during SLM. This inherently requires more energy.

These technologies are revolutionizing the manufacturing processes in various industries. There are applications in several industries for additive manufacturing, such as in Dental, Medical, Aerospace, Automotive, Pharmaceutical, and Consumer.

## The current status of AM

### Product development using AM

Additive manufacturing has been expanding and is reaching a level of maturity. What was once seen as a hobbyist/experimental pursuit has reached the production floor?

Using 3D printing technologies, the traditional product development route has been changed to a more streamlined approach that encompasses direct feedback to iteration design several times over.

With added benefits such as recyclable powder, the manufacturer can retain a high yield relative to powder supply during its SLS/DMLS printing process.

Not to mention the added complexity in the design. With additive manufacturing, the designer has flexibility in designing its parts since the manufacturing process is capable of producing such intricate and detailed assemblies.

Another added benefit of 3D Printing is the growing catalog of materials used. Formlabs boasts several different materials in their library of resins such as Tough, Clear, Engineering, and even Dental (biocompatible) resins.¹¹

Companies are incorporating more 3D technologies into their manufacturing scale and R&D projects to enhance their development process. According to Formlabs’ recent 2022 3D Printing Applications Report¹²:

> …48% of businesses use 3D Printing for small-batch custom piece production. Additionally, the frequent use of 3D Printing to create end-use parts is heavily skewed towards recent adopters, with 63% of recent adopters frequently or constantly using 3D printers for end-use components, compared to only 33% of early adopters.

Breaking down commonly used 3D Printing technologies:

> 56%, 44%, and 74% of recent adopters are using SLA, SLS and FDM technologies compared to early adopters (46%, 27%, and 78%), respectively.

The industry is changing in the direction of 3D Printing. Getting started in 3D Printing is more accessible than in the last two decades, with more options are available concerning different technologies, applications, resolution, hardware, and materials.

### Industry outlook of AM

As previously mentioned, there are currently several 3D printing technologies in the additive manufacturing space, making massive strides in various industries.

### Innovative companies in AM

I want to break down a few players utilizing additive manufacturing in various industries for this next section.

#### Formlabs

[Formlabs](https://formlabs.com/) is a 3D printing manufacturer based out of Somerville, Massachusetts. The company was founded in September 2011 at the MIT Media Lab. They’re mostly known for their Form printers which utilize their low-force stereolithography technology (SLA), which uses a light processing unit (LPU) to cure each segment in a layer.

Recently, they announced the first affordable desktop SLS machine, the Fuse 1. The entire package comes at a much cheaper price point of around $10,000. Applications for these printers include automotive, medical (huge player in dental right now), consumer, robotics, etc.

I’ve used their printers and software in the past and have had a lot of success with rapid prototyping and ease of use. They also offer a wide range of [material selection](https://formlabs.com/material-selector/) that continues to grow.

#### Aprecia Pharmaceuticals

Known as the leader of 3D pharmaceutical manufacturing, [Aprecia](https://www.aprecia.com/) focuses on 3D printing tablets that contain desired amounts of API thru our additive manufacturing process.

It is a form of binder jet printing that uses piezoelectric print jets, depositing binder material onto the powder substrate layer. Repeat this process several times, and you have a tablet. Like other AM technologies, predefined geometries allow for rigid structures to be created in detail.

Aprecia boasts the fact that¹⁴:

> Our three-dimensional printing (3DP) platform for pharmaceutical manufacturing is the first and only FDA-validated and ready today for commercial-scale drug development.

Two factors differentiate Aprecia’s platform technology:

1. Higher dose load with fast dispersion
2. Novel dosage forms and delivery modalities

Higher dose load alleviates the issue of pill burden by having a large dose. Instead of taking multiple pills, you can take much fewer. Coupled with fast dispersion, this makes it easier for the patient, especially those suffering from dysphagia (difficulty swallowing).

Novel dosage forms and delivery modalities can increase the drug count’s administration, allowing for a better and more customized patient experience.

The small company has been expanding its manufacturing capabilities with its recent partnership with R&D firm, Batelle.¹³

#### Relativity Space

Housing the world’s largest metal 3D printer, [Relativity Space](https://www.relativityspace.com/) has been making headway as the new company in the aerospace manufacturing field in the past few years.

This company found its roots in California and has grown immense momentum in creating the world’s first 3D printed rocket scheduled for launch early this year. It’s incredible to see what capabilities 3D printing has, and this is definitely no short order.

One of the major selling points is the number of parts used to create the rocket and the modernized manufacturing of the missile. In fact, Relativity Space says their process uses “100x fewer parts.”¹⁵

This simplifies the manufacturing substantially, allowing for continuous production since the rocket is built in fewer pieces. This company also utilizes robots and artificial intelligence to print the missiles.

It’s incredible to see a more accessible of complicated 3D Printing with the works of Formlabs and how it’s pushing the boundaries of space travel and customized patient treatment for all.

## The Future of AM

### Future technologies

A few points I want to cover in this section include:

- Dual extrusion
- Continual expansion of AM into various industries to support rapid prototyping and product development
- New material selection & properties
- Composite 3d Printing
- AI-enhanced AM
- Metal 3D printing advancement

### Dual Extrusion

The term is referred to as dual extrusion.¹⁶

Dual extrusion is precisely how it sounds. You’re depositing two different or same materials at different or same points in time.

Benefits to Dual Extrusion Printing:

- Eliminate the need for assembly
- Reduce the need for post-processing
- Promote efficient design of multifunctional objects
- Savings in cost and time

Dual extrusion is typically found on FDM/FFF printers. Dual extrusion uses two extrudes to eject two different or similar materials during a print job.

Ultimaker uses dual extrusion to print a component with one extruded and water-solvable support material. This makes post-processing simpler because support removal can be tedious, dangerous to the person doing the task, or damaging to the part.

One way to add dual extrusion capability to a 3d printer involves switching materials. Pause it during the print job and then switch the material to another. It is crucial to consider the pre-printing setup for said material, such as the heating temperature of the nozzle inside the extruder and heat bed.

Also, keep in mind the part cooling.

Depending on where the print is left off, it may start to cool down and not allow for proper adherence of the subsequent layers with the newly installed material.

All3DP lists “lack of control as one of the important limitations with this approach.” They suggest editing the g-code of the job to mitigate the issue.

As the name implies, another viable solution to incorporating dual extrusion is adding a second extruded. ALL3DP has a great guide detailing Dual Extrusion.¹⁷

There are other printers available in the market that have built-in dual printing functionality without the hassle of having to do it yourself.¹⁶

### Continual Expansion of AM into various industries to support rapid prototyping and product development

What was once seen as an experimental approach within the scope of only research and development has now reached the doors of production.

Additive manufacturing looks to mature into the large-scale production of goods by applying an innovative approach to producing products. This technology provides more control on the production, location, and material selection, to name a few positives.

It is no surprise that AM is making strides in various industries such as Aerospace, Medical Devices, Pharmaceuticals, Automotive, and Transportation.

One of the first applications that come to mind when considering AM is aerospace. Aerospace companies use additive manufacturing to experiment with different metals for their airplanes to help study which material selection and design are viable for performance.

The medical device industry incorporates AM into its lifecycle, not just in R&D but production as well. Like aerospace, the medical device industry uses AM to experiment with different material selections for biomimetic devices.

One interesting approach in this industry is the modification of 3d printers to support biocompatible materials. Since medical products interact with the body, they should possess biocompatibility properties to keep the immune system passive and avoid adverse effects.

Additive manufacturing also allows for the creation of scaffolding which uses 3d Printing to create “housing” for cells to grow on. By relying on similar human material properties, 3d Printing can achieve complex biomimetic structures that influence the growth of cells, bones, and organs as in the body.

A knee implant design can add complexity if desired and not be limited by traditional manufacturing processes. On a larger scale, 3d Printing also aids in creating bone implants.²⁶

The dental industry has also been making strides with 3D Printing. Formlabs created a dental high-performance 3D Printer known as the Form 3B along with dental, biocompatible resins used for creating molds, diagnostic, and aligner models.¹⁸

I knew that to build the mold, 3D scans would have to be done of my teeth, but I wasn’t sure how. Recently my dentists suggested I use a nightguard to help stop the degradation of my teeth during sleep. The assistant used a “wand” and scanned my teeth¹⁹, creating a 3d model of my mouth.

Long story short, in a few days, I received a night guard perfectly contoured to my teeth. If I had the cad model, I could reprint the night guards myself using my printers at home with a biocompatible material, probably the Form 3b.

The increase in rapid prototyping within various industries accelerates time to production and the increasing material selection, allowing new solutions across multiple domains.

### New material selection & properties

An inherent issue with 3D Printing is its relatively weak strength within the Z direction (depending on your printing orientation). This issue is more pronounced in FDM printing. Material selection can aid in this debacle.

3D printing filament can exhibit other characteristics favorable for more applications by infusing different materials.

> Composites produced by traditional means consist of a continuous or chopped fiber in ratios of 1,000 to 1 for applications demanding high material strength. Some new technologies have nanofiber-impregnated materials, particularly for the tooling and aerospace industries. These leverage polyamide composites (largely still proprietary formulations) filled with carbon fibers and fused in preprogrammed patterns that boost mechanical rigidity and resistance to chemicals and vibration.²⁰

This ties into the developing, extensive range of materials to choose from in additive manufacturing, which is impossible or is extending challenging to replicate in traditional systems.

### Composite 3D printing

Composite materials are made of two or more materials. Like the previous point, composite materials can be created depending on the application. Essentially by introducing different materials together, you’re able to modify and control the mechanical properties to suit your needs.

Several challenges, however, exist in composite manufacturing²¹:

- Expansion
- Cost
- Labor, resource-intensive

> Composite manufacturing is very labor, resource, and capital intensive, so it doesn’t really scale to large volumes. Additionally, there are long design cycles because of inadequate software and inefficient simulation — Wiener Mondesir, Co-Founder and Chief Technology Officer at Arevo.²¹

Innovative additive manufacturing is looking to combat these issues. To tackle the expansion, having an automated system is possible with internet-connected devices to govern the control of the printing cycle. You can get away with using different materials together to create composite material exhibiting products through AM.

Arevo announced the successful application of its composite 3D printing technology to manufacture bike frames. Thermwood’s Large Scale Additive Manufacturing technology is also gaining traction in composite tooling for aerospace applications.²¹

Technological advancements in material science and additive hardware can progress the material properties and applications of products made in various industries.

### AI-enhanced additive manufacturing

As discussed briefly above, smart manufacturing will continue to inch its way into mainstream production. The ability to control the material flow and the performance of the print in real-time can make the difference between a failed batch or saved parts.

By incorporating sensors and cameras within the print area, data acquired from the printing process can provide insights into maximizing performance. With machine learning, cameras can begin to detect potential defects using sensors. This can prevent failed print jobs in advance.

> Making 3D Printing more efficient and productive is an ongoing quest within the industry. One trend enabling this is the development of more intelligent systems powered by [sensors and machine learning](https://amfg.ai/2019/03/28/industry-4-0-7-real-world-examples-of-digital-manufacturing-in-action/). — Joshua Martin, CEO of Fortify²¹

[Generative design](https://www.autodesk.com/solutions/generative-design) has been becoming more popular recently. Essentially, the engineer or designer takes design inputs, sends that to the software, and generates designs based on that criteria. The engineer can begin to deduce from the provided permutations until a few viable candidates remain. The data acquired can also be used to optimize parts as well.

Companies such as VELO3D and MIT startup, Inkbit are working to provide sensor-equipped printers to monitor and provide quality data in real-time. More competent printers may identify, diagnose and prevent issues for future print jobs, allowing for on-the-go quality control and greater productivity.

### Metal 3D printing advancement

Newer advancements in additive manufacturing technology, such as powder-bed-based methods, will enable streamlined metal 3d printing. This can already be seen in various additive hardware manufacturers such as EOS, Desktop Metal, HP, and GE.

Disruption of traditional manufacturing is imminent given this fact. Metal 3D printing will continue to be used in a plethora of industries. Design complexity no longer becomes a constraint but a benefit to creativity. Of course, metal additive technology comes with its own hurdles.²²

I hope that we can see desktop metal machines made more accessible at a competitive price point in the near future. This would allow smaller business owners, startups, designers, engineers, and hobbyists to create using metal materials, thus expanding the capabilities of 3D Printing further.

Incorporating this into existing manufacturing processes can pose a challenge inherent to all additive technologies.

## Challenges

Several obstacles come into play as manufacturers integrate additive manufacturing practices into their production.

Some of the key challenges include:

- Startup cost
- Growing pains, meaning adjustability to the new process
- Available expertise
- Scalability (somewhat)

Depending on the technology suitable for your application, the cost to either build out a suite or buy out equipment can be tremendous. The price is highly dependent on what specific additive process you want to incorporate.

More affordable, accessible options exist now than they did in the last five years. However, the business needs to be considered heavily as the cost can become substantial when you factor in material, post-processing equipment, software, technicians, repairs, etc.

Alongside the cost, the growing pain of setting up the system and procedures in place for the new process takes time. New guidelines will have to be created to dictate pre-and post-processes.

Other learning gaps include how to design products tailored for additive manufacturing, what materials I need for my use case, or whether this process can replace or benefit my existing strategy.

Another major challenge is scalability. In production, manufacturing is inherently a numbers game, where producing at a large scale is typically beneficial, depending on the business. If you cannot meet the daily quota, you fall behind and risk losing customers no one wants.

Fortunately, additive printers increase printing volume and accessibility, making large-scale production possible. Stryker currently houses a 3D printing farm in Ireland to produce orthopedic implants.²³

Wanting to scale up will depend on the budget and target supply/demand you aim to satisfy. Expanding facilities ties into the first challenge — cost.

## Final Thoughts

Additive manufacturing will continue to mature over the next decade and impact all industries. 3D Printing will either replace traditional manufacturing in some companies or complement others. Software applications will become more streamlined, integrated, and suitable for additive.

However, the question becomes: how can AM compete with established, traditional manufacturing processes on cost, supply, and scalability? Will AM equipment costs continue to drop, allowing accessibility for more companies and creators?

If you enjoyed this article, let me know!

## References

[1] https://formlabs.com/blog/additive-manufacturing-vs-subtractive-manufacturing/

[2] https://www.3deo.co/strategy/costs-of-traditional-vs-additive-manufacturing/

[3] https://patents.google.com/patent/US3596285A/en

[4] https://www.3dprintingmedia.network/3d-hubs-publishes-complete-3d-printing-technologies-infographic/

[5] https://www.hubs.com/knowledge-base/what-is-fdm-3d-printing/

[6] https://formlabs.com/blog/ultimate-guide-to-stereolithography-sla-3d-printing/

[7] https://www.matterhackers.com/articles/how-to-succeed-when-sla-3d-printing-with-mh-build-resin

[8] https://formlabs.com/blog/what-is-selective-laser-sintering/

[9] https://technologystudent.com/despro_3/sintering1.html

[10] https://all3dp.com/2/selective-laser-melting-slm-3d-printing-simply-explained/

[11] https://formlabs.com/materials/

[12] https://formlabs.com/3d-printing-applications-report-2022/

[13] https://www.aprecia.com/news/aprecia-establishes-a-long-term-partnership-with-battelle

[14] https://www.aprecia.com/technology

[15] https://www.relativityspace.com/rockets

[16] https://all3dp.com/2/multi-material-3d-printing-an-overview/

[17] https://all3dp.com/2/dual-extrusion-3d-printing-simply-explained-2/

[18] https://dental.formlabs.com/

[19] https://all3dp.com/1/best-intraoral-3d-scanners-for-faster-dental-impressions/

[20] https://www.machinedesign.com/3d-printing-cad/article/21830505/the-future-of-additive-manufacturing

[21] https://amfg.ai/2019/08/21/10-predictions-on-the-future-of-3d-printing-expert-roundup/#8_Composite_3D_printing_will_offer_a_huge_market_opportunity

[22] https://amfg.ai/2018/05/01/5-problems-faced-when-3d-printing-metals-and-how-to-fix-them/

[23] https://3dprintingindustry.com/news/stryker-allots-share-of-225-8m-to-develop-3d-printing-rd-in-ireland-156966/ Stryker Allots Share of $225.8M To Develop 3D Printing R&D in Ireland

[24] https://twitter.com/relativityspace/status/1456676347124727808/photo/2

[25] https://www.ge.com/additive/additive-manufacturing

[26] https://www.medicaldesignandoutsourcing.com/how-stryker-is-using-3d-printing-to-advance-orthopedics/
