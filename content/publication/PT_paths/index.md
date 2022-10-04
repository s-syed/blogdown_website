---
abstract: Parallel tempering (PT) is a class of Markov chain Monte Carlo algorithms that constructs a path of distributions annealing between a tractable reference and an intractable target, and then interchanges states along the path to improve mixing in the target. The performance of PT depends on how quickly a sample from the reference distribution makes its way to the target, which in turn depends on the particular path of annealing distributions. However, past work on PT has used only simple paths constructed from convex combinations of the reference and target log-densities. This paper begins by demonstrating that this path performs poorly in the setting where the reference and target are nearly mutually singular. To address this issue, we expand the framework of PT to general families of paths, formulate the choice of path as an optimization problem that admits tractable gradient estimates, and propose a flexible new family of spline interpolation paths for use in practice. Theoretical and empirical results both demonstrate that our proposed methodology breaks previously-established upper performance limits for traditional paths.
author_notes:
- Equal contribution
- Equal contribution
authors:
- Vittorio Romaniello
- admin
- Trevor Campbell
- Alexandre Bouchard-Côté
date: "2021-07-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: ""
  focal_point: ""
  preview_only: false
publication: International Conference on Machine Learning
publication_short: In the *International Conference on Machine Learning*
publication_types:
- "1"
publishDate: ""
slides: ""
summary: ""
tags: []
title: Parallel tempering on optimized paths
url_code: ""
url_dataset: ""
url_preprint: ""
url_pdf: "https://arxiv.org/pdf/2102.07720.pdf"
url_poster: "uploads/poster_paths.pdf"
url_project: ""
url_slides: "uploads/slides_paths.pdf"
url_source: "http://proceedings.mlr.press/v139/syed21a.html"
url_video: "https://icml.cc/virtual/2021/spotlight/8924"

links:
- icon: ""
  icon_pack: fab
  name: Arxiv
  url: https://arxiv.org/abs/2102.07720
---