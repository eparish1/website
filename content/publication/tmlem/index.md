---
title: "Time-series machine-learning error models for approximate solutions to parameterized dynamical systems"
authors:
- admin
- Kevin T. Carlberg  
date: "2019-09-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This work proposes a machine-learning framework for modeling the error incurred by approximate solutions to parameterized dynamical systems. In particular, we extend the machine-learning error models (MLEM) framework proposed in Ref. 15 to dynamical systems. The proposed Time-Series Machine-Learning Error Modeling (T-MLEM) method constructs a regression model that maps features--which comprise error indicators that are derived from standard a posteriori error-quantification techniques--to a random variable for the approximate-solution error at each time instance. The proposed framework considers a wide range of candidate features, regression methods, and additive noise models. We consider primarily recursive regression techniques developed for time-series modeling, including both classical time-series models (e.g., autoregressive models) and recurrent neural networks (RNNs), but also analyze standard non-recursive regression techniques (e.g., feed-forward neural networks) for comparative purposes. Numerical experiments conducted on multiple benchmark problems illustrate that the long short-term memory (LSTM) neural network, which is a type of RNN, outperforms other methods and yields substantial improvements in error predictions over traditional approaches. 
# Summary. An optional shortened abstract.

tags:
- Machine learning
- time-series 
- long short-term memory 
featured: false

links:
url_pdf: https://arxiv.org/pdf/1907.11822.pdf 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
