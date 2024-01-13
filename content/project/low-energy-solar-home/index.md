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

My capstone group project is on designing a low-energy home with roof-top solar PV. In particular, I was responsible for the building envelope design and simulating the energy consumption. The building envelop consists of walls, ceiling, floors, and foundation. The wall design was inspired by the double stud wall system. This type of design has high thermal resistivity, is easy of integrate, and has inherent design redundancy, which protects wall integrity against degradation and damage. From outside to inside, the wall components consist of: exterior hardie board, furring strips, air and water barrier, plywood sheathing, wooden stud, rockwool insulation, vapour and air barrier, plywood sheathing, wooden stud, rockwool insulation, and interior gypsum board. The design for the walls are shown in Figure 1.
{style="text-align: justify;"}

{{< figure src="wall-side-view.jpg" caption="Storage sizing" numbered="true" >}}

The wall design is simulated in THERM to obtain its thermal resistivity, as shown in Figure 2. The wooden studs are thermal conductor, and seperating them in a double stud system effectively cut off the direct path for thermal conductance.
{style="text-align: justify;"}

{{< figure src="wall-thermal.jpg" caption="Storage sizing" numbered="true" >}}

The wall design is also simluted in WUFI to obtain the moisture characteristics, as shown in Figure 3. The simulation shows moisture will not accumulate inside the wall, which can cause molding and damage the structural integrity.
{style="text-align: justify;"}

{{< figure src="wall-moisture.jpg" caption="Storage sizing" numbered="true" >}}

The envelope design for the ceiling, floors, and foundation are shown in Figure 4 to 6. Each design was simulated in THERM and WUFI to determine its thermal and mositure characteristics.
{style="text-align: justify;"}

{{< figure src="wall-ceiling-side-view.jpg" caption="Storage size in context" numbered="true" >}}
{{< figure src="wall-floor-side-view.jpg" caption="Storage size in context" numbered="true" >}}
{{< figure src="wall-foundation-side-view.jpg" caption="Storage size in context" numbered="true" >}}

The entire house is simulated in HOT2000 to determine its heat loss and energy consumption, the results are shown in Figure 7.
{style="text-align: justify;"}

{{< figure src="energy-consumption-result.jpg" caption="Storage size in context" numbered="true" >}}

{style="text-align: justify;"}

