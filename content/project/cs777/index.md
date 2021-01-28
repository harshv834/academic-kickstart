---
title: Robust Training for Neural Networks
summary: Alt-opt based 1-layer ReLU training with LS for +ve and -ve weights and sparse recovery to choose the weights' signs.
tags:
- Deep Learning
- Optimization
date: "2019-01-05T23:37:28+05:30"

# Optional external URL for project (replaces project detail page).
external_link: "files/cs777_report.pdf"

weight: 20
#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "files/cs777_report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
Designed a novel alternating-optimization based training algorithm for a single hidden layer NN with ReLU activation by breaking the training procedure into 3 stages -sparse recovery for choosing the sign of weights and separate regression procedures for the positive and negative weights. Proved the rates of convergence for this algorithm under mild assumptions on the weights & input.

