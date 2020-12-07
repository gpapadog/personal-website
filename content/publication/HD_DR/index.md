---
title: "Causal inference in high dimensions: A marriage between Bayesian modeling and good frequentist properties"
authors:
- Joseph Antonelli
- admin
- Francesca Dominici
date: "2019-09-23"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Biometrics"
publication_short: "Biometrics"

abstract: We introduce a framework for estimating causal effects of binary and continuous treatments in high dimensions. The proposed framework extends many existing estimators introduced in the causal inference literature to high-dimensional settings. We discuss how posterior distributions of any treatment and outcome model can be used together with any causal estimator that is defined as a function of data, and treatment and outcome models (e.g. inverse probability weighted or doubly robust estimator). We propose an approach to uncertainty quantification of causal estimators that utilizes posterior distributions of model parameters that (1) results in good frequentist properties in small samples, (2) is based on a single MCMC, and (3) improves over frequentist measures of uncertainty which rely on asymptotic properties. We show that, for the doubly robust estimator, the posterior contraction rate is the product of the contraction rates of the treatment and outcome models. We consider a flexible framework for modeling the treatment and outcome processes within the Bayesian paradigm that reduces model dependence, accommodates nonlinearity, and achieves dimension reduction of the covariate space. We illustrate the ability of the proposed approach to flexibly estimate causal effects in high dimensions and appropriately quantify uncertainty, and show that it performs well relative to existing approaches. Finally, we estimate the effect of continuous environmental exposures on cholesterol and triglyceride levels. An R package is available at github.com/jantonelli111/DoublyRobustHD.

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: false

links:
- name: "R package"
  url: https://github.com/jantonelli111/DoublyRobustHD
- name: "arXiv"
  url: https://arxiv.org/abs/1805.04899
url_pdf: files/HD_DR.pdf
#url_code: 
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
slides: example
---

