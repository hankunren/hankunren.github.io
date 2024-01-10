---
title: Battery Energy Storage Sizing
summary: Novel method to size storage with the aim of maximizing storage utilization and eliminating wasted storage capcacity.
tags:
  - Energy Storage
date: '2016-04-27T00:00:00Z'

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

In alignment with the Paris Agreement, the city of Oxford in the UK aims to become carbon neutral by 2040. Renewable energy help achieve this target by reducing the reliance on carbon-intensive grid electricity. This research seeks to optimally size solar photovoltaic and lithium battery storage systems, reducing Oxford’s grid electricity reliance in buildings. The analysis starts with modeling the electricity demand. The model uses Elexon electricity settlement profiles, and assembles them into the demand profile according to the quantity and types of buildings in Oxford. Then, solar generation is modeled using Pfenninger and Staffell’s method. 
{style="text-align: justify;"}

{{< figure src="figure-system-setup.jpg" caption="Storage sizing" numbered="true" >}}

Solar photovoltaic and lithium storage systems are sized using a hybridized analytical and iterative method. First, the method calculates the solar system size search range, then iterates through the range. At each solar size, the method calculates and iterates through the storage system size search range. Within each iteration, the renewable system is simulated using demand and generation data with a simplified system setup and the conventional operation strategy. The method outputs combinations of solar system capacity, storage system capacity, and grid electricity import. Each combination’s levelized cost of electricity is calculated, and the lowest cost combination is the optimal sizing. 
{style="text-align: justify;"}

{{< figure src="figure-design-space.jpg" caption="Storage sizing" numbered="true" >}}

Solar and storage system costs are projected from 2019 to 2100, and the optimal sizing is calculated for each year. The result shows that solar photovoltaic is economically competitive, but lithium storage cost is still too high. As solar and storage prices continue to drop, they will take up greater portions of the energy system. However, there will always be a need for the grid, as it provides flexibility and can meet demands that are too costly for solar and storage. 
{style="text-align: justify;"}

{{< figure src="figure-future-system.jpg" caption="Storage sizing" numbered="true" >}}
