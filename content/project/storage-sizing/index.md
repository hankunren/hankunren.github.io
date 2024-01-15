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

This project is part of a journal paper titled 'Novel Method to Size Storage with the Aim of Maximizing Storage Utilization and Eliminating Wasted Storage Capacity,' published in the Journal of Energy Storage. The research introduces a novel analytical method for optimally sizing energy storage in microgrid systems. The method demonstrates fast calculation speeds, calculates the exact optimal, and handles non-linear models. The method first constructs a temporal storage profile of stored energy, based on how storage charges and discharges in response to renewable generation and load demand. The storage is sized according to the largest cumulative charge or discharge in the profile, as shown in Figure 1. Essentially, the storage profile represents how storage is utilized within a given system, and the method sizes the storage to maximize that profile, ensuring storage utilization is maximized and unutilized or wasted storage is eliminated.
{style="text-align: justify;"}

{{< figure src="figure-storage-sizing.jpg" caption="Solar–battery microgrid’s (a) unconstrained storage profile and (b) constrained storage profile." numbered="true" >}}

The method is applied to a solar-battery home case study to determine the storage size for each day, week, and month. The results, presented in Figure 2, indicate that peak summer and peak winter require smaller storage, while early summer and early autumn require larger storage. This is because high demand and generation necessitate larger storage, whereas low demand or low generation requires smaller storage.
{style="text-align: justify;"}

{{< figure src="figure-daily-weekly-monthly.jpg" caption="Storage size calculated using the (a) monthly, (b) weekly, and (c) daily design period." numbered="true" >}}

The study also demonstrates that increasing the storage size reduces the marginal increase in energy provided by storage, indicating diminishing returns. The thresholds for diminishing returns are defined by the largest daily and annual storage designs, as illustrated in Figure 3. The results show that the largest daily design only requires 3% of the annual design's storage size but provides 80% of the energy supplied by the annual design.
{style="text-align: justify;"}

{{< figure src="figure-storage-size-in-context.jpg" caption="Storage size and the associated energy provided to the microgrid" numbered="true" >}}

The proposed method can serve as a decision support tool for energy analysts to determine the required storage capacity when coupled with known renewable generation and load demand.
{style="text-align: justify;"}
