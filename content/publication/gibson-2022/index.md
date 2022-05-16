---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Using Multivariate Imputation by Chained Equations to Predict Redshifts of
  Active Galactic Nuclei
subtitle: ''
summary: ''
authors:
- Spencer James Gibson
- Aditya Narendra
- Maria Giovanna Dainotti
- Malgorzata Bogdan
- Agnieszka Pollo
- Artem Poliszczuk
- Enrico Rinaldi
- Ioannis Liodakis
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-05-16T14:38:33+09:00
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
publishDate: '2022-05-16T05:38:33.590571Z'
publication_types:
- '2'
abstract: Redshift measurement of active galactic nuclei (AGNs) remains a time-consuming
  and challenging task, as it requires follow up spectroscopic observations and detailed
  analysis. Hence, there exists an urgent requirement for alternative redshift estimation
  techniques. The use of machine learning (ML) for this purpose has been growing over
  the last few years, primarily due to the availability of large-scale galactic surveys.
  However, due to observational errors, a significant fraction of these data sets
  often have missing entries, rendering that fraction unusable for ML regression applications.
  In this study, we demonstrate the performance of an imputation technique called
  Multivariate Imputation by Chained Equations (MICE), which rectifies the issue of
  missing data entries by imputing them using the available information in the catalog.
  We use the Fermi-LAT Fourth Data Release Catalog (4LAC) and impute 24% of the catalog.
  Subsequently, we follow the methodology described in Dainotti et al. (ApJ, 2021,
  920, 118) and create an ML model for estimating the redshift of 4LAC AGNs. We present
  results which highlight positive impact of MICE imputation technique on the machine
  learning models performance and obtained redshift estimation accuracy.
publication: '*Frontiers in Astronomy and Space Sciences*'
doi: 10.3389/fspas.2022.836215
---
