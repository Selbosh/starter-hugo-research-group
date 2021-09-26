---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dimension-Independent MCMC Sampling for Inverse Problems with Non-Gaussian
  Priors
subtitle: ''
summary: ''
authors:
- Sebastian J Vollmer
tags: []
categories: []
date: '2015-01-01'
lastmod: 2021-09-26T12:37:57+02:00
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
publishDate: '2021-09-26T10:37:57.826120Z'
publication_types:
- '2'
abstract: The computational complexity of Markov chain Monte Carlo (MCMC) methods
  for the exploration of complex probability measures is a challenging and important
  problem in both statistics and the applied sciences. A challenge of particular importance
  arises in Bayesian inverse problems where the target distribution may be supported
  on an infinite-dimensional state space. In practice this involves the approximation
  of the infinite-dimensional target measure defined on sequences of spaces of increasing
  dimension bearing the risk of an increase of the computational error. Previous results
  have established dimension-independent bounds on the Monte Carlo error of MCMC sampling
  for Gaussian prior measures. We extend these results by providing a simple recipe
  for also obtaining these bounds in the case of non-Gaussian prior measures and by
  studying the design of proposal chains for the Metropolis--Hastings algorithm with
  dimension-independent performance. This study is motivated by an elliptic inverse
  problem with non-Gaussian prior that arises in groundwater flow. We explicitly construct
  an efficient Metropolis--Hastings proposal based on local proposals in this case,
  and we provide numerical evidence supporting the theory.
publication: '*SIAM/ASA J. Uncertainty Quantification*'
---
