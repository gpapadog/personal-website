---
title: "Bipartite causal inference with interference, time series data, and a random network"
authors:
- Zhaoyan Song
- admin
date: "2024-09-16"
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

abstract: In bipartite causal inference with interference, two distinct sets of units exist; interventional units, which receive treatment, and outcome units, where outcomes are measured. Which interventional units' treatment can drive which outcome units' outcomes is often depicted in a bipartite network. We study bipartite causal inference with interference from observational data across time and with a changing bipartite network. Under an exposure mapping framework, we define causal effects specific to each outcome unit, representing average contrasts of potential outcomes across time. We establish unconfoundedness of the exposure received by outcome units based on unconfoundedness assumptions on the interventional units' treatment assignment and the random graph, hence respecting the bipartite structure of the problem. Harvesting the time component of our setting, causal effects are estimable while controlling only for temporal trends and time-varying confounders. Our results hold for binary, continuous, and multivariate exposure mappings. For binary exposure, we propose three matching algorithms to estimate the causal effect by matching exposed to unexposed time periods for the same outcome unit. We show that the bias of resulting estimators is bounded. We illustrate our approach through simulation studies and a study on the effect of wildfire smoke on transportation by bicycle.


# Summary. An optional shortened abstract.
summary: A framework for causal inference with bipartite interference from observational, time series data with a random bipartite network.

tags:
- Source Themes
featured: true

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2404.04775
url_code: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

