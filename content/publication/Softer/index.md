---
title: "Soft tensor regression"
authors:
- admin
- Zhengwu Zhang
- David B. Dunson
date: "2019-10-22"
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

abstract: Statistical methods relating tensor predictors to scalar outcomes in a regression
model generally vectorize the tensor predictor and estimate the coefficients of its
entries employing some form of regularization, use summaries of the tensor covariate,
or use a low dimensional approximation of the coefficient tensor. However, low rank
approximations of the coefficient tensor can suffer if the true rank is not small. We
propose a tensor regression framework which assumes a soft version of the parallel
factors (PARAFAC) approximation. In contrast to classic PARAFAC, where each
entry of the coefficient tensor is the sum of products of row-specific contributions
across the tensor modes, the soft tensor regression (Softer) framework allows the row-specific
contributions to vary around an overall mean. We follow a Bayesian approach
to inference, and show that softening the PARAFAC increases model flexibility, leads
to more precise predictions, improved estimation of coefficient tensors, and more
accurate identification of important predictor entries, even for a low approximation
rank. From a theoretical perspective, we show that the posterior distribution of
the coefficient tensor based on Softer is weakly consistent irrespective of the true
tensor or approximation rank. In the context of our motivating application, we
adapt Softer to symmetric and semi-symmetric tensor predictors and analyze the
relationship between brain network characteristics and human traits

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: false

links:
- name: "arXiv"
  url: https://arxiv.org/abs/1910.09699
# url_pdf: files/hospitals.pdf
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

