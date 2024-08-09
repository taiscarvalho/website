---
title: "Urban Water Demand Modeling Using Machine Learning Techniques: Case Study of Fortaleza, Brazil"
authors:
- Nunes Carvalho, T. M.
- Souza Filho, F. D. A.
- Porto, V. C.

date: "2015-09-01T00:00:00Z"
doi: "10.1061/(ASCE)WR.1943-5452.0001310"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Water Resources Planning and Management"
publication_short: ""

abstract: Despite recent efforts to apply machine learning (ML) for water demand modeling, overcoming the black-box nature of these techniques to extract practical information remains a challenge, especially in developing countries. This study integrated random forest (RF), self-organizing map (SOM), and artificial neural network (ANN) techniques to assess water demand patterns and to develop a predictive model for the city of Fortaleza, Brazil. We performed the analysis at two spatial scales, with different level of information: census tracts (CTs) at the fine scale, and census blocks (CBs) at the coarse scale. At the CB scale, demand was modeled with socioeconomic, demographic, and household characteristics. The RF technique was applied to rank these variables, and the most relevant were used to cluster census blocks with SOMs. RFs and ANNs were used in an iterative approach to define the input variables for the predictive model with minimum redundancy. At the CT scale, demand was modeled using HDI and per capita income. Variables which assess the education level and economic aspects of households demonstrated a direct relationship with water demand. The analysis at the coarse scale provided more insight into the relationship between the variables; however, the predictive model performed better at the fine scale. This study demonstrates how data-driven models can be helpful for water management, especially in environments with strong socioeconomic inequalities, where urban planning decisions should be integrated and inclusive.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: [https://link.springer.com/article/10.1007/s11356-022-21168-z]
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/taiscarvalho/chla-prediction-ce'
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

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
---