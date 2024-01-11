---
title: "Energy storage capacity sizing and site placement in renewable systems using optimal power flow to minimize generator cost and maximize storage utilization"
authors:
- admin
- Malcolm McCulloch
- David Wallom
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This paper presents a novel analytical method for sizing and placing energy storage, with the objective of maximizing storage utilization and minimizing generator costs. The method exhibits fast performance, accommodates non-convex models, and converges effectively to optimal sizing and placement. The method first employs optimal power flow to optimize storage power dispatch. Then, storage profiles are constructed based on the storage dispatch. Subsequently, storage sizing and placement are calculated from these profiles. The proposed method is benchmarked against both meta-heuristic and mathematical optimization methods. The benchmark demonstrates that the proposed method yields the smallest storage size that minimizes generator cost. Moreover, the benchmark finds that storage tends to be placed on sites with large generation, large demand, or near congested lines with high power flow. The method is applied to a case study on a carbon-neutral village with wind and solar generation. The study finds that the storage requirement is the highest when renewable generations are just enough to support the system. Additional renewable generators can reduce the storage requirement, but only up to a certain extent. This is because storage remains necessary to support demand during calm nights with no solar or wind generation. The proposed method serves as a decision support tool for energy system planners, aiding in optimal storage sizing and placement given known generation and demand.

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false


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
- storage-placement-and-sizing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---