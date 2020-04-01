---
title: "Mitigating Unobserved spatial confounding when estimating the effect of supermarket access on cardiovascular disease deaths"
authors:
- Patrick Schnell
- admin
date: "2020-03-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In Revisions"
publication_short: "In Revisions"

abstract: Confounding by unmeasured spatial variables has received some attention in the spatial statistics and causal inference literatures, but concepts and approaches have remained largely separated. In this paper, we aim to bridge these distinct strands of statistics by considering unmeasured spatial confounding within a causal inference framework, and estimating effects using outcome regression tools popular within the spatial literature. First, we show how using spatially correlated random effects in the outcome model, an approach common among spatial statisticians, does not necessarily mitigate bias due to spatial confounding, a previously published but not universally known result. Motivated by the bias term of commonly-used estimators, we propose an affine estimator which addresses this deficiency. We discuss how unbiased estimation of causal parameters in the presence of unmeasured spatial confounding can only be achieved under an untestable set of assumptions which will often be application-specific. We provide a set of assumptions which describe how the exposure and outcome of interest relate to the unmeasured variables, and which is sufficient for identification of the causal effect based on the observed data. We examine identifiability issues through the lens of restricted maximum likelihood estimation in linear models, and implement our method using a fully Bayesian approach applicable to any type of outcome variable. This work is motivated by and used to estimate the effect of county-level limited access to supermarkets on the rate of cardiovascular disease deaths in the elderly across the whole continental United States. Even though standard approaches return null or protective effects, our approach uncovers evidence of unobserved spatial confounding, and indicates that limited supermarket access has a harmful effect on cardiovascular mortality.

# Summary. An optional shortened abstract.
summary: Addressing confounding bias from unmeasured spatial variables using mixed models.

tags:
- Source Themes
featured: false

links:
- name: "arXiv"
  url: https://arxiv.org/abs/1907.12150
- name: "Slides"
  url: files/slides_SpatialConfounding2.pdf
# url_pdf: files/hospitals.pdf
url_code: 'https://github.com/schnellp/causal-spatial'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Limited access to supermarkets by county'
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
slides: example
---

