---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Modeling racial/ethnic differences in COVID-19 incidence with covariates subject to non-random missingness'
subtitle: ''
summary: ''
authors:
- admin
- Yang Chen
- Jon Zelner
tags:
- Statistics - Methodology
- Statistics - Applications
categories: []
date: '2022-06-16'
lastmod: 2022-06-16T16:38:51-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-06-16T20:38:51.650202Z'
publication_types:
- '3'
abstract: Characterizing the cumulative burden of COVID-19 by race/ethnicity is of the utmost importance for public health researchers and policy makers in order to design effective mitigation measures. This analysis is hampered, however, by surveillance case data with substantial missingness in race and ethnicity covariates. Worse yet, this missingness likely depends on the values of these missing covariates, i.e. they are not missing at random (NMAR). We propose a Bayesian parametric model that leverages joint information on spatial variation in the disease and covariate missingness processes and can accommodate both MAR and NMAR missingness. We show that the model is locally identifiable when the spatial distribution of the population covariates is known and observed cases can be associated with a spatial unit of observation. We also use a simulation study to investigate the model's finite-sample performance. We compare our model's performance on NMAR data against complete-case analysis and multiple imputation (MI), both of which are commonly used by public health researchers when confronted with missing categorical covariates. Finally, we model spatial variation in cumulative COVID-19 incidence in Wayne County, Michigan using data from the Michigan Department and Health and Human Services. The analysis suggests that population relative risk estimates by race during the early part of the COVID-19 pandemic in Michigan were understated for non-white residents compared to white residents when cases missing race were dropped or had these values imputed using MI.
publication: '*Accepted at Annals of Applied Statistics*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2206.08161
---
