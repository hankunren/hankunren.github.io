---
title: Battery Energy Storage Sizing
summary: Novel method to size storage with the aim of maximizing storage utilization and eliminating wasted storage capcacity.
tags:
  - Storage
date: '2023-09-15T00:00:00Z'

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

This project is part of a journal paper titled "Novel method to size storage with the aim of maximizing storage utilization and eliminating wasted storage capcacity" published in the Journal of Energy Storage. The research presents a novel analytical method to optimally size energy storage in microgrid systems. The method has fast calculation speeds, calculates the exact optimal, and handles non-linear models. The method first constructs a temporal storage profile of stored energy, based on how storage charges and discharges in response to renewable generation and load demand. The storage is sized according to the largest cumulative charge or discharge in the profile, as shown in Figure 1. In essence, the storage profile represents how storage is utilized within a given system, and the method sizes optimal storage to maximize that profile, such that storage utilization is maximized, and unutilized or wasted storage is eliminated. 
{style="text-align: justify;"}

{{< figure src="figure-storage-sizing.jpg" caption="Solar–battery microgrid’s (a) unconstrained storage profile and (b) constrained storage profile." numbered="true" >}}

The method is applied to a solar-battery home case study to obtain the storage size for each day, each week, and each month. The results are shown in Figure 2, which show that high demand and generation require larger storage, while low demand or low generation requires smaller storage. For these reasons, peak summer and peak winter require smaller storage, while early summer and early autumn require larger storage. 
{style="text-align: justify;"}

{{< figure src="figure-daily-weekly-monthly.jpg" caption="Storage size calculated using the (a) monthly, (b) weekly, and (c) daily design period." numbered="true" >}}

The study also shows increasing the storage size reduces the marginal increase in energy provided by storage, indicating diminishing returns. The diminishing return thresholds are defined by the largest daily and annual storage designs, as shown in Figure 3. The result shows the largest daily design only requires 3% of the annual design's storage size, but provides 80% of the energy provided by the annual design. 
{style="text-align: justify;"}

{{< figure src="figure-storage-size-in-context.jpg" caption="Storage size and the associated energy provided to the microgrid" numbered="true" >}}

The proposed method can be used as a decision support tool for energy analysts, to determine required storage capacity when coupled with known renewable generation and load demand.
{style="text-align: justify;"}
