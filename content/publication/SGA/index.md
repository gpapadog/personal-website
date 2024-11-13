---
title: "Propensity Score Weighting for Causal Subgroup Analysis"
authors:
- Siyun Yang
- Elizabeth Lorenzi
- admin
- Daniel M. Wojdyla
- fan_li_duke
- Laine E. Thomas
date: "2021-05-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Statistics in Medicine"
publication_short: "Statistics in Medicine"

abstract: A common goal in comparative effectiveness research is to estimate treatment effects on prespecified subpopulations of patients. Though widely used in medical research, causal inference methods for such subgroup analysis (SGA) remain underdeveloped, particularly in observational studies. In this article, we develop a suite of analytical methods and visualization tools for causal SGA. First, we introduce the estimand of subgroup weighted average treatment effect and provide the corresponding propensity score weighting estimator. We show that balancing covariates within a subgroup bounds the bias of the estimator of subgroup causal effects. Second, we propose to use the overlap weighting (OW) method to achieve exact balance within subgroups. We further propose a method that combines OW and LASSO, to balance the bias-variance tradeoff in SGA. Finally, we design a new diagnostic graph—the Connect-S plot—for visualizing the subgroup covariate balance. Extensive simulation studies are presented to compare the proposed method with several existing methods. We apply the proposed methods to the patient-centered results for uterine fibroids (COMPARE-UF) registry data to evaluate alternative management options for uterine fibroids for relief of symptoms and quality of life.


# Summary. An optional shortened abstract.
summary: Causal inference for subgroup analysis and the Connect-S plot.

tags:
- Source Themes
featured: false

links:
- name: "arXiv"
  url: https://arxiv.org/abs/2010.02121
- name: "Journal"
  url: https://doi.org/10.1002/sim.9029
url_code: https://github.com/siyunyang/OW_SGA

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Connect-S plot: Visualizing subgroup balance'
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
slides: ""
---

