---
title: "Mitigating unobserved spatial confounding bias with mixed models"
authors:
- Patrick Schnell
- admin
date: "2019-07-28"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Under review."
publication_short: "Under review."

abstract: Confounding by unmeasured spatial variables has received some attention in the spatial statistics and causal inference literatures, but concepts and approaches have remained largely separated. In this paper, we aim to bridge these distinct strands of statistics by considering unmeasured spatial confounding within a formal causal inference framework, and estimating effects using modifications of outcome regression tools popular within the spatial literature. First, we show that using spatially correlated random effects in the outcome model, an approach common among spatial statisticians, does not mitigate bias due to spatial confounding. Motivated by the bias term of commonly-used estimators, we propose an affine estimator which addresses this deficiency. We discuss how unbiased estimation of causal parameters in the presence of unmeasured spatial confounding can only be achieved under an untestable set of assumptions which will often be application-specific. We provide one set of assumptions that is sufficient for identification of the causal effect based on the observed data. These assumptions describe how the exposure and outcome of interest relate to the unmeasured variables. Estimation of the model components necessary for unbiased estimation of the causal effect proceeds using tools common in the spatial statistics literature, and specifically via a regularized restricted maximum likelihood approach employing weakly informative priors to avoid degenerate estimates. This work is motivated by and used to estimate the causal effect of county-level (a) exposure to emissions from coal-powered electricity generating units, and (b) relative humidity on particulate matter across the New England area in the United States, and to investigate the potential threat from unmeasured spatial confounders in this context.

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
url_dataset: 'https://github.com/schnellp/causal-spatial'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

