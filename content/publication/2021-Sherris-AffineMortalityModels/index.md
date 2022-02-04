---
title: "Multi-factor, Age-Cohort, Affine Mortality Models: A Multi-Country Comparison"
authors:
- Francesco Ungolo
- admin
- yzhou
date: "2021-08-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: CEPAR Working Paper
publication_short: CEPAR Working Paper

abstract: Affine mortality models, developed in continuous time, are well suited to longevity applications including pricing and risk management. Advantages of this modelling approach include closed-form derivations of cohort survival curves, with these survival curves consistent with the dynamics of mortality rates. We compare a number of multi-factor continuous time affine models applied to age-cohort mortality data in a multi-country comparison of five countries with differing lengths of time series mortality data. We develop improved estimation methods for these models and provide R code. Parameters are estimated using maximum likelihood with the univariate Kalman Filter, which accounts for the Poisson variation in the measurement equation. We show how this estimation method is faster and more robust compared to the traditional formulation which heavily uses large matrix multiplication and inversion. We also discuss and address numerical issues with the estimation process. We provide graphical and numerical goodness-of-fit checks, and assess model robustness. We then project cohort survival curves and assess the out-of-sample performance of the analysed models. Although the CIR mortality model fits historical data well, particularly at older ages. Other affine mortality models provide better out-of-sample performance, although less so old ages. We show that the affine mortality models analysed are robust with respect to the set of age-cohort data used for parameter estimation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Longevity Risk
- Kalman Filter
- State-Space Models
featured: true

links:
- name: View at CEPAR website
  url: https://www.cepar.edu.au/publications/working-papers/multi-factor-age-cohort-affine-mortality-models-multi-country-comparison
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
projects: sample

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
