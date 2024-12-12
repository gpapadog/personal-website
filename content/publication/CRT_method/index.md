---
title: "Addressing selection bias in cluster randomized experiments via weighting"
authors:
- admin
- Bo Liu
- fan_li_yale
- fan_li_duke
date: "2024-12-04"
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

abstract: In cluster randomized experiments, individuals are often recruited after the cluster treatment assignment, and data are typically only available for the recruited sample. Post-randomization recruitment can lead to selection bias, inducing systematic differences between the overall and the recruited populations, and between the recruited intervention and control arms. In this setting, we define causal estimands for the overall and the recruited populations. We prove, under the assumption of ignorable recruitment, that the average treatment effect on the recruited population can be consistently estimated from the recruited sample using inverse probability weighting. Generally we cannot identify the average treatment effect on the overall population. Nonetheless, we show, via a principal stratification formulation, that one can use weighting of the recruited sample to identify treatment effects on two meaningful subpopulations of the overall population, individuals who would be recruited into the study regardless of the assignment, and individuals who would be recruited into the study under treatment but not under control. We develop an estimation strategy and a sensitivity analysis approach for checking the ignorable recruitment assumption. The proposed methods are applied to the ARTEMIS cluster randomized trial, where removing co-payment barriers increases the persistence of P2Y12 inhibitor among the always-recruited population.


# Summary. An optional shortened abstract.
summary: In cluster randomized experiments with selection bias due to recruitment, data are often only available on those that were recruited. Based on a principal stratification framework, we show that causal effects on the overall population are identifiable based on the recruited sample only.

tags:
- Source Themes
featured: true

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2309.07365
- name: "R package"
  url: https://github.com/gpapadog/CRTrecruit
url_pdf: files/CRT.pdf

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

