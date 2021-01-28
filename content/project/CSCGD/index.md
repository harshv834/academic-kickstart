---
title: Constrained Stochastic Compositional Gradient Descent
summary: Convergence analysis of constrained formulation of compositional SGD
tags:
- Optimization
date: "2019-01-05T23:29:29+05:30"

# Optional external URL for project (replaces project detail page).
external_link: ""

weight: 10
#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
links:
- name: PDF
  url : https://arxiv.org/pdf/2012.09400.pdf

url_code: ""
#url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

This work studies constrained stochastic optimization problems where the objective and constraint functions are convex and expressed as compositions of stochastic functions. The problem arises in the context of fair classification, fair regression, and the design of queuing systems. Of particular interest is the large-scale setting where an oracle provides the stochastic gradients of the constituent functions, and the goal is to solve the problem with a minimal number of calls to the oracle. The problem arises in fair classification/regression and in the design of queuing systems. Owing to the compositional form, the stochastic gradients provided by the oracle do not yield unbiased estimates of the objective or constraint gradients. Instead, we construct approximate gradients by tracking the inner function evaluations, resulting in a quasi-gradient saddle point algorithm. We prove that the proposed algorithm is guaranteed to find the optimal and feasible solution almost surely. We further establish that the proposed algorithm requires O(ϵ^(-4)) data samples in order to obtain an ϵ-approximate optimal point while also ensuring zero constraint violation. The result matches the sample complexity of the stochastic compositional gradient descent method for unconstrained problems and improves upon the best-known sample complexity results for the constrained settings. The efficacy of the proposed algorithm is tested on both fair classification and fair regression problems. The numerical results show that the proposed algorithm outperforms the state-of-the-art algorithms in terms of the convergence rate.
