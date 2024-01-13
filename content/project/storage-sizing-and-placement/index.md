---
title: Energy Storage Sizing and Placement
summary: Energy storage capacity sizing and site placement in renewable systems using optimal power flow to minimize generator cost and maximize storage utilization.
tags:
  - Storage
  - Featured
date: '2023-12-01T00:00:00Z'

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

This research presents a novel analytical method for sizing and placing energy storage, with the objective of maximizing storage utilization and minimizing generator costs. The method exhibits fast performance, accommodates non-convex models, and converges effectively to optimal sizing and placement. The method first employs optimal power flow to optimize storage power dispatch. Then, storage profiles are constructed based on the storage dispatch. Subsequently, storage sizing and placement are calculated from these profiles. A summary of the method is shown in Figure 1. 
{style="text-align: justify;"}

{{< figure src="figure-method-overview.jpg" caption="Summary of the proposed method on sizing and placing energy storage." numbered="true" >}}

The proposed method is benchmarked against both meta-heuristic and mathematical optimization methods. The benchmark demonstrates that the proposed method yields the smallest storage size that minimizes generator cost. Moreover, the benchmark finds that storage tends to be placed on sites with large generation, large demand, or near congested lines with high power flow, as shown in Figure 2. 
{style="text-align: justify;"}

{{< figure src="figure-storage-map-24.jpg" caption="Storage size and placement using the proposed method with AC OPF and linear storage model in the IEEE Reliability Test System." numbered="true" >}}

The method is applied to a case study on a carbon-neutral village with wind and solar generation. The storage size and placement for the village with two wind turbines and 4 kW solar PV per building is shown in Figure 3. 
{style="text-align: justify;"}

{{< figure src="figure-storage-map-500.jpg" caption="Storage size and placement using the proposed method with AC OPF in the carbon-neutral village." numbered="true" >}}

The study finds that the storage requirement is the highest when renewable generations are just enough to support the system, as shown in Figure 4.  Additional renewable generators can reduce the storage requirement, but only up to a certain extent. This is because storage remains necessary to support demand during calm nights with no solar or wind generation. 
{style="text-align: justify;"}
{{< figure src="figure-wind-solar-variation.jpg" caption="ensitivity analysis on the effect of solar and wind capacity variation on (a) total storage size, and (b) energy exchange with the external grid." numbered="true" >}}


The proposed method serves as a decision support tool for energy system planners, aiding in optimal storage sizing and placement given known generation and demand.