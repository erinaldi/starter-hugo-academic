---
title: "Toward Generative Quantum Utility via Correlation-Complexity Map"
authors:
  - Chen-Yu Liu
  - Leonardo Placidi
  - Eric Brunner
  - me
date: "2026-03-06"
publication_types:
  - article
abstract: "We study a practical question in generative quantum machine learning: given a classical dataset, can we determine, before training, whether it is well suited to a quantum generative model? We focus on a class of quantum circuits known as instantaneous quantum polynomial-time (IQP) circuits, whose output distributions are widely believed to be difficult to sample from using classical methods. These circuits are used to build our quantum generative models. We introduce a Correlation-Complexity Map, a simple diagnostic built from two quantities computed from data samples. The first measures how closely the dataset's spectral correlation patterns resemble those naturally produced by IQP circuits, while the second quantifies how much of the dataset's structural correlation cannot be captured by simple pairwise models. In other words, we can estimate beforehand how well a dataset can be approximated by our model family and also how complex its correlations are, indicating possible failures of classical models. Applying this framework, we identify turbulence data as a promising target for quantum generative modeling. Guided by this analysis, we use a latent-parameter adaptation scheme that reuses a compact IQP circuit over a temporal sequence by learning and interpolating a low-dimensional latent trajectory, and observe competitive performance against classical baselines in a low-data, low-parameter regime. These results suggest that dataset-level diagnostics can help prioritize problems where quantum generative models are most likely to be useful, with improvements in data and parameter efficiency."
hugoblox:
  ids:
    arxiv: "2603.06440"
links:
  - type: source
    url: https://inspirehep.net/literature/3127430
    label: INSPIRE
featured: false
---
