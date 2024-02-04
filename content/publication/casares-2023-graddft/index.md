---
title: 'GradDFT: a software library for machine learning enhanced density functional
  theory'
authors:
- Pablo Antonio Moreno Casares
- Jack S Baker
- Matija Medvidovic
- Roberto dos Reis
- Juan Miguel Arrazola
date: '2023-01-01'
publishDate: '2024-02-04T20:39:57.260902Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2309.15127*'
featured: true
#image: '/content/publication/casares-2023-graddft/Neural_functional_concept.pdf'
image:
  caption: 'Schematic depiction of the [general workflow for machine learning-enhanced density functional theory](/content/publication/casares-2023-graddft/Neural_functional_concept.pdf)'
  focal_point: ''
  preview_only: false
  src: '/content/publication/casares-2023-graddft/Neural_functional_concept.pdf'

url_code: 'https://github.com/XanaduAI/GradDFT'

abstract: "Density functional theory (DFT) stands as a cornerstone method in computational quantum chemistry and materials science due to its remarkable versatility and scalability. Yet, it suffers from limitations in accuracy, particularly when dealing with strongly correlated systems. To address these shortcomings, recent work has begun to explore how machine learning can expand the capabilities of DFT; an endeavor with many open questions and technical challenges. In this work, we present Grad DFT: a fully differentiable JAX-based DFT library, enabling quick prototyping and experimentation with machine learning-enhanced exchange-correlation energy functionals. Grad DFT employs a pioneering parametrization of exchange-correlation functionals constructed using a weighted sum of energy densities, where the weights are determined using neural networks. Moreover, Grad DFT encompasses a comprehensive suite of auxiliary functions, notably featuring a just-in-time compilable and fully differentiable self-consistent iterative procedure. To support training and benchmarking efforts, we additionally compile a curated dataset of experimental dissociation energies of dimers, half of which contain transition metal atoms characterized by strong electronic correlations. The software library is tested against experimental results to study the generalization capabilities of a neural functional across potential energy surfaces and atomic species, as well as the effect of training data noise on the resulting model accuracy."
---
