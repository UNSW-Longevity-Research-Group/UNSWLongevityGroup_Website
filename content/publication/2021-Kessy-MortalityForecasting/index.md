---
title: "Mortality forecasting using stacked regression ensembles"
authors:
- skessy
- admin
- avillegas
- jziveyi
date: "2021-11-16"
doi: "10.1080/03461238.2021.1999316"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-16"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Scandinavian Actuarial Journal
publication_short: Scandinavian Actuarial Journal

abstract: Many alternative approaches for selecting mortality models and forecasting mortality have been proposed. The usual practice is to base forecasts on a single mortality model selected using in-sample goodness-of-fit measures. However, cross-validation measures are increasingly being used in model selection, and model combination methods are becoming a common alternative to using a single mortality model. We propose and assess a stacked regression ensemble that optimally combines different mortality models to reduce out-of-sample mean squared errors and mitigate model selection risk. Stacked regression uses a meta-learner to approximate horizon-specific weights by minimizing a cross-validation criterion for each forecasting horizon. The horizon-specific weights determine a mortality model combination customized to each horizon. We use 44 populations from the Human Mortality Database to compare the stacked regression ensemble with alternative methods. We show that, using one-year-ahead to 15-year-ahead out-of-sample mean squared errors, the stacked regression ensemble improves mortality forecast accuracy by 13% - 49% for males and 19% - 90% for females over individual mortality models. The stacked regression ensembles also have better predictive accuracy than other model combination methods, including Simple Model Averaging, Bayesian Model Averaging, and Model Confidence Set. We provide an R package, CoMoMo, that combines forecasts for Generalized-Age-Period-Cohort models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Stacked regression
- Ensemble learning
- Cross-validation
- Model uncertainty
- Model combination
- Age-period-cohort model
- Mortality forecasting
featured: true

links:
- name: View at CEPAR website
  url: https://www.cepar.edu.au/publications/working-papers/mortality-forecasting-using-stacked-regression-ensembles
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
slides:
---
