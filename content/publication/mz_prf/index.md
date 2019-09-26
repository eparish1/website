---
title: "Non-Markovian closure models for large eddy simulations using the Mori-Zwanzig formalism"
authors:
- admin
- Karthik Duraisamy  
date: "2017-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This work uses the Mori-Zwanzig (M-Z) formalism, a concept originating from nonequilibrium statistical mechanics, as a basis for the development of coarse-grained models of turbulence. The mechanics of the generalized Langevin equation (GLE) are considered, and insight gained from the orthogonal dynamics equation is used as a starting point for model development. A class of subgrid models is considered which represent nonlocal behavior via a finite memory approximation [Stinis, arXiv:1211.4285 (2012)], the length of which is determined using a heuristic that is related to the spectral radius of the Jacobian of the resolved variables. The resulting models are intimately tied to the underlying numerical resolution and are capable of approximating non-Markovian effects. Numerical experiments on the Burgers equation demonstrate that the M-Z-based models can accurately predict the temporal evolution of the total kinetic energy and the total dissipation rate at varying mesh resolutions. The trajectory of each resolved mode in phase space is accurately predicted for cases where the coarse graining is moderate. Large eddy simulations (LESs) of homogeneous isotropic turbulence and the Taylor-Green Vortex show that the M-Z-based models are able to provide excellent predictions, accurately capturing the subgrid contribution to energy transfer. Last, LESs of fully developed channel flow demonstrate the applicability of M-Z-based models to nondecaying problems. It is notable that the form of the closure is not imposed by the modeler, but is rather derived from the mathematics of the coarse graining, highlighting the potential of M-Z-based techniques to define LES closures. 
tags:
- Closure modeling
- Large Eddy Simulation
- Mori-Zwanzig formalism 
featured: false

links:
url_pdf: https://journals.aps.org/prfluids/abstract/10.1103/PhysRevFluids.2.014604 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Energy dissipation for the Taylor Green Vortex'
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
