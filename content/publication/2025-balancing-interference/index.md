---
title: "Low-rank Covariate Balancing Estimators under Interference"
authors:
- Souhardya Sengupta
- Kosuke Imai
- admin
date: "2025-12-17"
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

abstract: A key methodological challenge in observational studies with interference between units is twofold, (1) each unit's outcome may depend on many others' treatments, and (2) treatment assignments may exhibit complex dependencies across units. We develop a general statistical framework for constructing robust causal effect estimators to address these challenges. We first show that, without restricting the patterns of interference, the standard inverse probability weighting (IPW) estimator is the only uniformly unbiased estimator when the propensity score is known. In contrast, no estimator has such a property if the propensity score is unknown. We then introduce a low-rank structure of potential outcomes as a broad class of structural assumptions about interference. This framework encompasses common assumptions such as anonymous, nearest-neighbor, and additive interference, while flexibly allowing for more complex study-specific interference assumptions. Under this low-rank assumption, we show how to construct an unbiased weighting estimator for a large class of causal estimands. The proposed weighting estimator does not require knowledge of true propensity scores and is therefore robust to unknown treatment assignment dependencies that often exist in observational studies. If the true propensity score is known, we can obtain an unbiased estimator that is more efficient than the IPW estimator by leveraging a low-rank structure. We establish the finite sample and asymptotic properties of the proposed weighting estimator, develop a data-driven procedure to select among candidate low-rank structures, and validate our approach through simulation and empirical studies.




# Summary. An optional shortened abstract.
summary: In the presence of interference, IPW estimators often suffer from high variance. Under low-rank assumptions on the potential outcomes and in the presence of interference, we design optimal covariate balancing estimators. The framework encompasses commonly-invoked assumptions such as stratified or additive interference.

tags:
- Source Themes
featured: true

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2512.13944
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
  caption: ''
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

