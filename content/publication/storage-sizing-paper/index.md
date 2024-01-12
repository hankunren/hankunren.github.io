---
title: "An analytical method for sizing energy storage in microgrid systems to maximize renewable consumption and minimize unused storage capacity"
authors:
- admin
- Masao Ashtine
- Malcolm McCulloch
- David Wallom
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-09-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Energy Storage*"
publication_short: ""

abstract: This paper presents a novel analytical method to optimally size energy storage in microgrid systems. The method has fast calculation speeds, calculates the exact optimal, and handles non-linear models. The method first constructs a temporal storage profile of stored energy, based on how storage charges and discharges in response to renewable generation and load demand. The storage is sized according to the largest cumulative charge or discharge in the profile. In essence, the storage profile represents how storage is utilized within a given system, and the method sizes optimal storage to maximize that profile, such that storage utilization is maximized, and unutilized or wasted storage is eliminated. Maximizing storage utilization also maximizes renewable consumption and minimizes load shedding, as storage utilization is the temporal transfer of energy from renewable generation to load demand. The proposed method is extended iteratively to account for storage’s energy limits, power limits, and energy leakage. Two solar–battery case studies demonstrate the method. The first study shows that optimally sized storage does not have wasted capacity due to over-sizing, nor cause energy deficits due to under-sizing. The second case study shows increasing the storage size reduces the marginal increase in energy provided by storage, indicating diminishing returns. The diminishing return thresholds are defined by the largest daily and annual storage designs. The result shows the largest daily design only requires 3% of the annual design’s storage size, but provides 80% of the energy provided by the annual design. The proposed method can be used as a decision support tool for energy analysts, to determine required storage capacity when coupled with known renewable generation and load demand.

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false

links:
  - name: Paper
    url: https://www.sciencedirect.com/science/article/pii/S2352152X23011325
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
  - storage-sizing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
