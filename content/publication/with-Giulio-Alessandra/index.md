---
title: "Spatial vertical regression for spatial panel data: Evaluating the effect of the Florentine tramway's first line on commercial vitality"
authors:
- Giulio Grossi
- Alessandra Mattei
- admin
date: "2025-05-02"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Synthetic control methods are commonly used in panel data settings to evaluate the effect of an intervention. In many of these cases, the treated and control units correspond to spatial units such as regions or neighborhoods. Our approach addresses the challenge of understanding how an intervention applied at specific locations influences the surrounding area. Traditional synthetic control applications may struggle with defining the effective area of impact, the extent of treatment propagation across space, and the variation of effects with distance from the treatment sites. To address these challenges, we introduce Spatial Vertical Regression (SVR) within the Bayesian paradigm. This innovative approach allows us to accurately predict the outcomes in varying proximities to the treatment sites, while meticulously accounting for the spatial structure inherent in the data. Specifically, rooted on the vertical regression framework of the synthetic control method, SVR employs a Gaussian process to ensure that the imputation of missing potential outcomes for areas of different distance around the treatment sites is spatially coherent, reflecting the expectation that nearby areas experience similar outcomes and have similar relationships to control areas. This approach is particularly pertinent to our study on the Florentine tramway's first line construction. We study its influence on the local commercial landscape, focusing on how business prevalence varies at different distances from the tram stops.


# Summary. An optional shortened abstract.
summary: When the treated units are spatial areas, their relationship with the control units is expected to exhibit a spatial relationship. Under the vertical regression framework, we propose a Bayesian approach for estimation of causal effects with spatial panel data.

tags:
- Source Themes
featured: true

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2505.00450
url_pdf: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The realized and hypothetical tramway lines with buffers of 2, 4, 6, 8, and 10 minute walking distance of the tram stops.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

