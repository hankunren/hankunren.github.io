---
title: Solar Photovoltaics and Battery Storage Sizing
summary: Optimal sizing of solar photovoltaic and lithium battery storage to reduce grid electricity reliance in buildings.
tags:
  - Solar
  - Featured
date: '2022-08-01T00:00:00Z'

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
This project is part of a conference paper titled 'Optimal sizing of solar photovoltaic and lithium battery storage to reduce grid electricity reliance in buildings,' published in the ECEEE conference. The research aims to optimally size solar photovoltaic and lithium battery storage systems, reducing the city of Oxford’s grid electricity reliance in buildings. The setup of the solar-battery system is illustrated in Figure 1.
{style="text-align: justify;"}

{{< figure src="figure-system-setup.jpg" caption="Hybrid renewable solar-battery system setup" numbered="true" >}}

Solar photovoltaic and lithium storage systems are sized using a hybridized analytical and enumerative method. Initially, the method calculates the search range for the solar PV system size. Subsequently, it systematically iterates through this size search range. At each solar size, the method calculates the search range for the battery storage system size, and then systematically iterates through that size search range. Within each iteration, the renewable system is simulated using demand and generation data with a conventional operational strategy. The method outputs combinations of solar system capacity, storage system capacity, and grid electricity import, as illustrated in Figure 2.
{style="text-align: justify;"}

{{< figure src="figure-design-space.jpg" caption="Design space with solar capacity, storage capacity, and annual grid electricity import" numbered="true" >}}

The levelized cost of electricity is calculated for each combination, and the optimal sizing is determined by selecting the combination with the lowest cost. Solar and storage system costs are projected from 2019 to 2100, and optimal sizing is calculated for each year in the projection. The results, depicted in Figure 3, indicate that currently, solar PV is economically competitive, but the cost of lithium battery storage is still too high. As solar and storage prices continue to decrease, they will take up larger portions of the energy system. However, there will always be a need for the power grid, as it provides flexibility at a competitive cost.
{style="text-align: justify;"}

{{< figure src="figure-future-system.jpg" caption="Optimal solar capacity, storage capacity, and grid electricity import according to NREL renewable cost projection." numbered="true" >}}
