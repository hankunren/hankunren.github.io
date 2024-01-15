---
title: Low Energy Solar Home
summary: Building envelope design and energy simulation of a low energy solar home.
tags:
  - Demand
date: '2019-04-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
slides: ''
---

My capstone group project focused on the design of a low-energy home incorporating rooftop solar PV. My responsibility entailed designing the building envelope and simulating energy consumption of the home. The building envelope comprised of walls, ceiling, floors, and foundation. The wall design drew inspiration from the double stud wall system, chosen for its high thermal resistivity, ease of integration, and inherent design redundancy that safeguards wall integrity against degradation and damage.

From the exterior to the interior, the wall components include: exterior Hardie board, furring strips, air and water barrier, plywood sheathing, wooden stud, rockwool insulation, vapor and air barrier, plywood sheathing, wooden stud, rockwool insulation, and interior gypsum board. The detailed wall design is depicted in Figure 1.
{style="text-align: justify;"}

{{< figure src="wall-side-view.jpg" caption="Storage sizing" numbered="true" >}}

The wall design is simulated in THERM to determine its thermal resistivity, as illustrated in Figure 2. The wooden studs act as thermal conductors, and separating them in a double stud system effectively interrupts the direct path for thermal conductance.
{style="text-align: justify;"}

{{< figure src="wall-thermal.jpg" caption="Storage sizing" numbered="true" >}}

The wall design is also simulated in WUFI to obtain moisture characteristics, as depicted in Figure 3. The simulation indicates that moisture will not accumulate inside the wall, mitigating the risk of molding and damage to the structural integrity.
{style="text-align: justify;"}

{{< figure src="wall-moisture.jpg" caption="Storage sizing" numbered="true" >}}

The envelope designs for the ceiling, floors, and foundation are depicted in Figures 4 to 6. Each design was simulated in THERM and WUFI to determine its thermal and moisture characteristics.
{style="text-align: justify;"}

{{< figure src="wall-ceiling-side-view.jpg" caption="Storage size in context" numbered="true" >}}
{{< figure src="wall-floor-side-view.jpg" caption="Storage size in context" numbered="true" >}}
{{< figure src="wall-foundation-side-view.jpg" caption="Storage size in context" numbered="true" >}}

The entire house was simulated in HOT2000 to determine its heat loss and energy consumption. The results are shown in Figure 7.
{style="text-align: justify;"}

{{< figure src="energy-consumption-result.jpg" caption="Storage size in context" numbered="true" >}}


