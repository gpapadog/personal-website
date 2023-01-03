---
title: "Covariate-informed latent interaction models: Addressing geographic & taxonomic bias in predicting bird-plant interactions"
authors:
- admin
- Carolina Bello
- Otso Ovaskainen
- David B. Dunson
date: "2021-03-09"
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

abstract: Climate change and reductions in natural habitats necessitate that we better understand species’ interactivity and how biological communities respond to environmental changes. How- ever, ecological studies of species’ interactions are limited by geographic and taxonomic bias which can lead to severe under-representation of certain species and distort our understanding of inter-species interactions. We illustrate that ignoring these biases can result in poor perfor- mance. We develop a model for predicting species’ interactions that a) accounts for errors in the recorded interaction networks, b) addresses the geographic and taxonomic bias of exist- ing studies, c) is based on latent factors to increase flexibility and borrow information across species, d) incorporates covariates in a flexible manner to inform the latent factors, and e) uses a meta-analysis data set from 166 individual studies. We focus on interactions among 242 birds and 511 plants in the Brazilian Atlantic Forest, and identify 5% of pairs of species with an un- recorded interaction, but posterior probability of existing that is over 80%. Finally, we develop a permutation-based variable importance procedure and identify that a bird’s body mass and a plant’s fruit diameter are most important in driving the presence and detection of species interactions, with a multiplicative relationship.


# Summary. An optional shortened abstract.
summary: We propose a latent factor interaction model for networks measure with error, and a variable importance metric for latent models. We use the model to address the geographic and taxonomic bias of ecological studies of species' interactions, and identify the important bird and plant covariates for forming and detecting interactions.

tags:
- Source Themes
featured: true

links:
- name: "Arxiv"
  url: https://arxiv.org/abs/2103.05557
- name: "R package"
  url: https://github.com/gpapadog/BiasedNetwork
- name: "Analysis"
  url: https://github.com/gpapadog/Bird_Plant_Interactions
url_pdf: files/birds_and_plants.pdf
url_code: ''
url_dataset: 'https://doi.org/10.1002/ecy.1818'
url_poster: ''
url_project: ''
url_slides: files/slides_birds_plants.pdf
url_source: ''
url_video: 'https://www.youtube.com/watch?v=kK0VW8q2a80'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Multiplicative relationship of species traits for the probability of interaction'
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

