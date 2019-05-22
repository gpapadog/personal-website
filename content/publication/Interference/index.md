---
title: "Causal inference with interfering units for cluster and population level treatment allocation programs"
authors:
- admin
- Fabrizia Mealli
- Corwin M. Zigler
date: "2019-03-11"
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
publication_short: ""

abstract: Interference arises when an individual's potential outcome depends on the individual treatment level, but also on the treatment level of others. A common assumption in the causal inference literature in the presence of interference is partial interference, implying that the population can be partitioned in clusters of individuals whose potential outcomes only depend on the treatment of units within the same cluster. Previous literature has defined average potential outcomes under counterfactual scenarios where treatments are randomly allocated to units within a cluster. However, within clusters there may be units that are more or less likely to receive treatment based on covariates or neighbors’ treatment. We define new estimands that describe average potential outcomes for realistic counterfactual treatment allocation programs, extending existing estimands to take into consideration the units’ covariates and dependence between units’ treatment assignment. We further propose entirely new estimands for population‐level interventions over the collection of clusters, which correspond in the motivating setting to regulations at the federal (vs. cluster or regional) level. We discuss these estimands, propose unbiased estimators and derive asymptotic results as the number of clusters grows. For a small number of observed clusters, a bootstrap approach for confidence intervals is proposed. Finally, we estimate effects in a comparative effectiveness study of power plant emission reduction technologies on ambient ozone pollution.


# Summary. An optional shortened abstract.
summary: Causal inference with interference for realistic treatment allocation programs. Evaluating the comparitive effectiveness of power plant emission reduction strategies for reducing ambient ozone concentrations.

tags: []
featured: false

links:
- name: "Journal"
  url: https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13049
- name: "Package"
  url: https://github.com/gpapadog/Interference
- name: "Slides"
  url: files/daps_interference_slides.pdf
url_pdf: files/Interference.pdf
#url_pdf: 
url_code: 
url_dataset: https://dataverse.harvard.edu/dataverse/dapsm
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
