---
title: "Stochastic Compositional Gradient Descent under Compositional Constraints"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Srujan T Thomdapu
- Harshvardhan
- Ketan Rajawat

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted in Mathematical Programming 
publication_short: arXiv

#abstract: This work studies constrained stochastic optimization problems where the objective and constraint functions are convex and expressed as compositions of stochastic functions. The problem arises in the context of fair classification, fair regression, and the design of queuing systems. Of particular interest is the large-scale setting where an oracle provides the stochastic gradients of the constituent functions, and the goal is to solve the problem with a minimal number of calls to the oracle. The problem arises in fair classification/regression and in the design of queuing systems. Owing to the compositional form, the stochastic gradients provided by the oracle do not yield unbiased estimates of the objective or constraint gradients. Instead, we construct approximate gradients by tracking the inner function evaluations, resulting in a quasi-gradient saddle point algorithm. We prove that the proposed algorithm is guaranteed to find the optimal and feasible solution almost surely. We further establish that the proposed algorithm requires O(1/ϵ4) data samples in order to obtain an ϵ-approximate optimal point while also ensuring zero constraint violation. The result matches the sample complexity of the stochastic compositional gradient descent method for unconstrained problems and improves upon the best-known sample complexity results for the constrained settings. The efficacy of the proposed algorithm is tested on both fair classification and fair regression problems. The numerical results show that the proposed algorithm outperforms the state-of-the-art algorithms in terms of the convergence rate.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.09400.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- CSCGD

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
