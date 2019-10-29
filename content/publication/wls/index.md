---
title: "Windowed least-squares model reduction for dynamical systems"
authors:
- admin
- Kevin T. Carlberg  
date: "2019-10-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This work proposes a windowed least-squares (WLS) approach for model-reduction of dynamical systems. The proposed approach sequentially minimizes the time-continuous full-order-model residual within a low-dimensional space-time trial subspace over time windows. The approach comprises a generalization of existing model reduction approaches, as particular instances of the methodology recover Galerkin, least-squares Petrov-Galerkin (LSPG), and space-time LSPG projection. In addition, the approach addresses key deficiencies in existing model-reduction techniques, e.g., the dependence of LSPG and space-time LSPG projection on the time discretization and the exponential growth in time exhibited by a posteriori error bounds for both Galerkin and LSPG projection. We consider two types of space-time trial subspaces within the proposed approach, one that reduces only the spatial dimension of the full-order model, and one that reduces both the spatial and temporal dimensions of the full-order model. For each type of trial subspace, we consider two different solution techniques: direct (i.e., discretize then optimize) and indirect (i.e., optimize then discretize). Numerical experiments conducted using trial subspaces characterized by spatial dimension reduction demonstrate that the WLS approach can yield more accurate solutions with lower space-time residuals than Galerkin and LSPG projection.

 
# Summary. An optional shortened abstract.

tags:
- model-order reduction
- least-squares
- Petrov-Galerkin
featured: false 

links:
url_pdf: https://arxiv.org/pdf/1910.11388.pdf 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
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
