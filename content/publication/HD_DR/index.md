---
title: "Causal inference in high dimensions: A marriage between Bayesian modeling and good frequentist properties"
authors:
- Joseph Antonelli
- admin
- Francesca Dominici
date: "2022-03-17"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Biometrics"
publication_short: "Biometrics"

abstract: We introduce a framework for estimating causal effects of binary and continuous treatments in high dimensions. We show how posterior distributions of treatment and outcome models can be used together with doubly robust estimators. We propose an approach to uncertainty quantification for the doubly robust estimator, which utilizes posterior distributions of model parameters and (1) results in good frequentist properties in small samples, (2) is based on a single run of a Markov chain Monte Carlo (MCMC) algorithm, and (3) improves over frequentist measures of uncertainty which rely on asymptotic properties. We consider a flexible framework for modeling the treatment and outcome processes within the Bayesian paradigm that reduces model dependence, accommodates nonlinearity, and achieves dimension reduction of the covariate space. We illustrate the ability of the proposed approach to flexibly estimate causal effects in high dimensions and appropriately quantify uncertainty. We show that our proposed variance estimation strategy is consistent when both models are correctly specified, and we see empirically that it performs well in finite samples and under model misspecification. Finally, we estimate the effect of continuous environmental exposures on cholesterol and triglyceride levels.

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
- name: "Journal"
  url: https://doi.org/10.1111/biom.13417
#url_pdf: files/HD_DR.pdf
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

