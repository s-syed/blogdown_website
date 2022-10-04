---
abstract: Sampling from complex target distributions is a challenging task fundamental to Bayesian inference. Parallel tempering (PT) addresses this problem by constructing a Markov chain on the expanded state space of a sequence of distributions interpolating between the posterior distribution and a fixed reference distribution, which is typically chosen to be the prior. However, in the typical case where the prior and posterior are nearly mutually singular, PT methods are computationally prohibitive. In this work we address this challenge by constructing a generalized annealing path connecting the posterior to an adaptively tuned variational reference. The reference distribution is tuned to minimize the forward (inclusive) KL divergence to the posterior distribution using a simple, gradient-free moment-matching procedure. We show that our adaptive procedure converges to the forward KL minimizer, and that the forward KL divergence serves as a good proxy to a previously developed measure of PT performance. We also show that in the large-data limit in typical Bayesian models, the proposed method improves in performance, while traditional PT deteriorates arbitrarily. Finally, we introduce PT with two references -- one fixed, one variational -- with a novel split annealing path that ensures stable variational reference adaptation. The paper concludes with experiments that demonstrate the large empirical gains achieved by our method in a wide range of realistic Bayesian inference scenarios.

authors:
- Nikola Surjanovic
- admin
- Trevor Campbell
- Alexandre Bouchard-Côté
date: "2022-05-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: ""
  focal_point: ""
  preview_only: false
publication: Conference on Neural Information Processing Systems
publication_short: To appear in the *Conference on Neural Information Processing Systems (Accepted)*
publication_types:
- "1"
publishDate: ""
slides: ""
summary: ""
tags: []
title: Parallel tempering with a variational reference
url_code: ""
url_dataset: ""
url_pdf: "https://arxiv.org/pdf/2206.00080.pdf"
url_poster: "uploads/poster_variational.pdf"
url_project: ""
url_slides: ""
url_source: "https://arxiv.org/abs/2206.00080"
url_video: ""
---