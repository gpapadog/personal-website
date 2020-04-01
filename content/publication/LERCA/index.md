---
title: "A Causal Exposure Response Function with Local Adjustment for Confounding: A study of the health effects of long-term exposure to low levels of fine particulate matter"
authors:
- admin
- Francesca Dominici
date: "2020-02-20"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "To appear -- Annals of Applied Statistics"
publication_short: "To appear. AOAS"

abstract: In the last two decades, ambient levels of air pollution have declined substantially. Yet, as mandated by the Clean Air Act, we must continue to address the following question. Is exposure to levels of air pollution that are well below the National Ambient Air Quality Standards (NAAQS) harmful to human health? Furthermore, the highly contentious nature surrounding environmental regulations necessitates casting this question within a causal inference framework. Several parametric and semi-parametric regression modeling approaches have been used to estimate the exposure-response (ER) curve relating long-term exposure to air pollution and various health outcomes. However, most of these approaches are not formulated in the context of a potential outcome framework for causal inference, adjust for the same set of potential confounders across all levels of exposure, and do not account for model uncertainty regarding covariate selection and the shape of the ER. In this paper, we introduce a Bayesian framework for the estimation of a causal ER curve called LERCA (Local Exposure Response Confounding Adjustment). LERCA allows for a) different confounders and different strength of confounding at the different exposure levels; and b) model uncertainty regarding confounders’ selection and the shape of the ER. Also, LERCA provides a principled way of assessing the observed covariates’ confounding importance at different exposure levels, providing environmental researchers with important information regarding the set of variables to measure and adjust for in regression models. Using simulation studies, we show that state of the art approaches perform poorly in estimating the ER curve in the presence of local confounding. Lastly, LERCA is used on a large data set which includes health, weather, demographic, and pollution information for 5,362 zip codes and for the years of 2011-2013.

# Summary. An optional shortened abstract.
summary: Causal exposure-response curve estimation with local confonding adjustment. Different variables confound the exposure-response relationship at different exposure levels.

tags:
- Source Themes
featured: false

links:
- name: "R package"
  url: https://github.com/gpapadog/LERCA
- name: "arXiv"
  url: https://arxiv.org/abs/1806.00928
# url_pdf: files/
#url_code: https://github.com/gpapadog/LERCA
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Evidence of local confounding'
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

