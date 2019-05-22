---
title: "Adjusting for unmeasured spatial confounding with distance adjusted propensity score matching"
authors:
- admin
- Christine Choirat
- Corwin M. Zigler
date: "2018-01-20"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Biostatistics"
publication_short: "Biostatistics"

abstract: Propensity score matching is a common tool for adjusting for observed confounding in observational studies, but is known to have limitations in the presence of unmeasured confounding. In many settings, researchers are confronted with spatially-indexed data where the relative locations of the observational units may serve as a useful proxy for unmeasured confounding that varies according to a spatial pattern. We develop a new method, termed distance adjusted propensity score matching (DAPSm) that incorporates information on units’ spatial proximity into a propensity score matching procedure. We show that DAPSm can adjust for both observed and some forms of unobserved confounding and evaluate its performance relative to several other reasonable alternatives for incorporating spatial information into propensity score adjustment. The method is motivated by and applied to a comparative effectiveness investigation of power plant emission reduction technologies designed to reduce population exposure to ambient ozone pollution. Ultimately, DAPSm provides a framework for augmenting a “standard” propensity score analysis with information on spatial proximity and provides a transparent and principled way to assess the relative trade-offs of prioritizing observed confounding adjustment versus spatial proximity adjustment. 

# Summary. An optional shortened abstract.
summary: Incorporating geographical distance in a propensity score matching approach to account for unmeasured confounding by spatial variables. 

tags:
- Source Themes
featured: false

links:
- name: "Journal"
  url: https://academic.oup.com/biostatistics/article/20/2/256/4818356
- name: "Slides"
  url: files/daps_interference_slides.pdf
url_pdf: files/dapsm.pdf 
url_code: https://github.com/gpapadog/DAPSm
url_dataset: https://dataverse.harvard.edu/dataverse/dapsm
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
