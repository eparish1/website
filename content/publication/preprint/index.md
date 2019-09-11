---
title: "The Adjoint--Petrov Galerkin Method for Non-linear Model Reduction"
authors:
- admin
- Christopher Wentland
- Karthik Duraisamy
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We formulate a new projection-based reduced-ordered modeling technique for non-linear dynamical systems. The proposed technique, which we refer to as the Adjoint Petrov-Galerkin (APG) method, is derived by decomposing the generalized coordinates of a dynamical system into a resolved coarse-scale set and an unresolved fine-scale set. A Markovian finite memory assumption within the Mori-Zwanzig formalism is then used to develop a reduced-order representation of the coarse-scales. This procedure leads to a closed reduced-order model that displays commonalities with the adjoint stabilization method used in finite elements. The formulation is shown to be equivalent to a Petrov-Galerkin method with a non-linear, time-varying test basis, thus sharing some similarities with the least-squares Petrov-Galerkin method. Theoretical analysis examining a priori error bounds and computational cost is presented. Numerical experiments on the compressible Navier-Stokes equations demonstrate that the proposed method can lead to improvements in numerical accuracy, robustness, and computational efficiency over the Galerkin method on problems of practical interest. Improvements in numerical accuracy and computational efficiency over the least-squares Petrov-Galerkin method are observed in most cases.
 
# Summary. An optional shortened abstract.

tags:
- Reduced-order modeling 
- Mori-Zwanzig 
- Petrov--Galerkin 
featured: false

links:
url_pdf: https://arxiv.org/pdf/1810.03455.pdf

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
