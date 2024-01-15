---
title: Construction Permit Tracker
summary: Automated tracker for permit status and construction schedule to facilitate the concurrent progressions of both.
tags:
  - Data
date: '2018-05-01T00:00:00Z'

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

At TC Energy, my project manager requested a program to track the permit status of construction sites. I developed the permit tracker using Excel VBA, where users input sites of interest, and the program identifies the associated permit status from the permit deptarment database via SharePoint. Additionally, the program compares the permit status with the construction schedule, providing warnings to the project manager of potential conflicts. This tool empowers project managers to concurrently manage construction progression and permit applications across hundreds of sites. The user interface of the tracker is illustrated in Figure 1.
{style="text-align: justify;"}

{{< figure src="schedule-option.jpg" caption="Storage sizing" numbered="true" >}}

The tracking results are shown in Figure 2. The program highlights sites with potential conflicts between permit status and the construction schedule, enabling project managers to proactively reschedule sites to ensure permit compliance.
{style="text-align: justify;"}

{{< figure src="schedule-track.jpg" caption="Storage sizing" numbered="true" >}}


