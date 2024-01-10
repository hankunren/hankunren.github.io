---
title: ECEEE Conference

event: ECEEE Conference
event_url: https://www.eceee.org/summerstudy/

location: Belambra Clubs "Les Criques"
address:
  street: Presqu'Ile de Giens, les-Palmiers
  city: Hyères
  region:
  postcode: '83400'
  country: France

summary: Presentation on solar and storage sizing given at the ECEEE conference.
abstract: 'In alignment with the Paris Agreement, Oxfordshire county in the United Kingdom aims to become carbon neutral by 2050. Renewable energy help achieve this target by reducing the reliance on carbon-intensive grid electricity. Thus, this research seeks to determine the optimal solar generation and lithium battery storage size to reduce building grid electricity reliance. The analysis starts with modeling the hourly electricity demand. The model uses Elexon building electricity settlement profiles, and assembles them into the hourly demand profile according to the quantity and types of buildings in Oxfordshire. Then, the hourly solar generation is modeled using Pfenninger and Staffell method. Solar photovoltaic and lithium batteries are sized using an iterative method. First, the method iterates through the solar size search range. At each solar size, the method then iterates through the storage size search range. The renewable system is simulated at each iteration using hourly demand and generation data with a simplified system setup and the conventional operation strategy. The sizing method outputs combinations of solar size, battery size, and the resulting grid electricity consumption. The levelized cost of electricity for each combination is calculated, and the lowest cost combination is the optimal sizing. Solar and battery costs are projected from 2019 to 2100, and the optimal sizing is calculated for each year. The result shows that solar generation is cheap but not as flexible as the grid. Battery storage can provide flexibility, but it is too expensive and therefore not utilized. Thus, the optimal solar system is sized to only meet the demand during peak generation, reducing excess generation that cannot be stored. However, as solar and battery prices continue to drop, they will take up greater portions of the energy system, and reduce more grid electricity demand.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: 

links:
url_code: ''
url_pdf: ''
url_slides: 'static/ECEEE-conference-presentation.pdf'
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - [storage-and-solar-sizing]
---



Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
