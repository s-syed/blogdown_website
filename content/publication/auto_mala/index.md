---
abstract: Selecting the step size for the Metropolis-adjusted Langevin algorithm (MALA) is necessary in order to obtain satisfactory performance. However, finding an adequate step size for an arbitrary target distribution can be a difficult task and even the best step size can perform poorly in specific regions of the space when the target distribution is sufficiently complex. To resolve this issue we introduce autoMALA, a new Markov chain Monte Carlo algorithm based on MALA that automatically sets its step size at each iteration based on the local geometry of the target distribution. We prove that autoMALA has the correct invariant distribution, despite continual automatic adjustments of the step size. Our experiments demonstrate that autoMALA is competitive with related state-of-the-art MCMC methods, in terms of the number of log density evaluations per effective sample, and it outperforms state-of-the-art samplers on targets with varying geometries. Furthermore, we find that autoMALA tends to find step sizes comparable to optimally-tuned MALA when a fixed step size suffices for the whole domain.

author_notes:
- Equal contribution
- Equal contribution
authors:
- Miguel Biron-Lattes
- Nikola Surjanovic
- admin
- Trevor Campbell
- Alexandre Bouchard-Côté
date: "2023-10-25T00:00:00Z"
doi: ""
featured: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
publication: 'Arxiv Preprint'
publication_short: ""
publication_types:
- "2"
publishDate: "2023-10-253T00:00:00Z"
slides: ""
summary: ""
tags:
title: "autoMALA: Locally adaptive Metropolis-adjusted Langevin algorithm"
url_code: ""
url_dataset: ""
url_pdf: "https://arxiv.org/abs/2310.16782.pdf"
url_preprint: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

links:
- icon: ""
  icon_pack: fab
  name: Arxiv
  url: https://arxiv.org/abs/2310.16782
---




