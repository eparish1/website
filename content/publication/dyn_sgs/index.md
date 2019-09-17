---
title: "A dynamic subgrid scale model for Large Eddy Simulations based on the Mori–Zwanzig formalism"
authors:
- admin
- Karthik Duraisamy  
date: "2017-04-07T00:00:00Z"
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

abstract: The development of reduced models for complex multiscale problems remains one of the principal challenges in computational physics. The optimal prediction framework of Chorin et al. [1], which is a reformulation of the Mori–Zwanzig (M–Z) formalism of non-equilibrium statistical mechanics, provides a framework for the development of mathematically-derived reduced models of dynamical systems. Several promising models have emerged from the optimal prediction community and have found application in molecular dynamics and turbulent flows. In this work, a new M–Z-based closure model that addresses some of the deficiencies of existing methods is developed. The model is constructed by exploiting similarities between two levels of coarse-graining via the Germano identity of fluid mechanics and by assuming that memory effects have a finite temporal support. The appeal of the proposed model, which will be referred to as the ‘dynamic-MZ-τ’ model, is that it is parameter-free and has a structural form imposed by the mathematics of the coarse-graining process (rather than the phenomenological assumptions made by the modeler, such as in classical subgrid scale models). To promote the applicability of M–Z models in general, two procedures are presented to compute the resulting model form, helping to bypass the tedious error-prone algebra that has proven to be a hindrance to the construction of M–Z-based models for complex dynamical systems. While the new formulation is applicable to the solution of general partial differential equations, demonstrations are presented in the context of Large Eddy Simulation closures for the Burgers equation, decaying homogeneous turbulence, and turbulent channel flow. The performance of the model and validity of the underlying assumptions are investigated in detail. 
# Summary. An optional shortened abstract.

tags:
- Closure modeling
- Large Eddy Simulation
- Mori-Zwanzig formalism 
featured: false

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S0021999117305612 

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
