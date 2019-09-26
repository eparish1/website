---
title: "A paradigm for data-driven predictive modeling using field inversion and machine learning"
authors:
- admin
- Karthik Duraisamy  
date: "2016-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We propose a modeling paradigm, termed field inversion and machine learning (FIML), that seeks to comprehensively harness data from sources such as high-fidelity simulations and experiments to aid the creation of improved closure models for computational physics applications. In contrast to inferring model parameters, this work uses inverse modeling to obtain corrective, spatially distributed functional terms, offering a route to directly address model-form errors. Once the inference has been performed over a number of problems that are representative of the deficient physics in the closure model, machine learning techniques are used to reconstruct the model corrections in terms of variables that appear in the closure model. These reconstructed functional forms are then used to augment the closure model in a predictive computational setting. As a first demonstrative example, a scalar ordinary differential equation is considered, wherein the model equation has missing and deficient terms. Following this, the methodology is extended to the prediction of turbulent channel flow. In both of these applications, the approach is demonstrated to be able to successfully reconstruct functional corrections and yield accurate predictive solutions while providing a measure of model form uncertainties. 
tags:
- Machine Learning 
- RANS 
- Data-Driven Modeling
- Field Inversion 
featured: false

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S0021999115007524 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
