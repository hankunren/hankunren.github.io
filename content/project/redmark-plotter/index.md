---
title: Redmark Automation on Cathodic Protection 
summary: Automating the placement of cathodic protection devices on engineering redmark drawings to streamline the process and improved accuracy.
tags:
  - CAD
  - Featured
date: '2018-08-10T00:00:00Z'

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

Each year, the corrosion prevention team at TC Energy has to produce hundreds of drawings with the location of thousands of cathodic protection devices to be installed. This task is estimated to take more than 200 hours annualy. The task is semi-automated through Excel using VBA programming, which streamlined engineering drawing process and improved drawing accuracy. The user interface of the program is shown in Figure 1.
{style="text-align: justify;"}

{{< figure src="redmark-plotter.jpg" caption="User interface for the cathodic protection redmark plotter" numbered="true" >}}

The program asks the user to trace the line on the drawing and identify its real-world location. Then, the program search through the database for locations of cathodic protection devices, selects the devices in that line's location, and plots them onto the engineering redmark drawing. The resulting redmark drawing is shown in Figure 2.
{style="text-align: justify;"}

{{< figure src="redmark-plot.jpg" caption="Example remark from the plotter" numbered="true" >}}

