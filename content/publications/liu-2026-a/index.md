---
title: "Generative IQP Circuit Learning with Physics-Informed Latent Initialization"
authors:
  - Chen-Yu Liu
  - Leonardo Placidi
  - Marco Ballarin
  - me
date: "2026-07-30"
publication_types:
  - article
abstract: "Quantum generative learning based on instantaneous quantum polynomial-time (IQP) circuits can benefit from efficient classical training strategies. A recent latent adaptation framework for IQP-based generative modeling transfers shared circuit parameters across instances of the same task with different hyperparameters while adapting only a low-dimensional latent variable for each new instance. However, existing approaches initialize this latent variable randomly, which can limit optimization efficiency and performance. In this work, we introduce a physics-informed latent initialization scheme for IQP generative learning to improve upon existing random initialization schemes. Motivated by the platonic representation hypothesis, we use latent representations extracted from a classical physics-informed neural network (PINN) surrogate to initialize the latent variables of the quantum model for the solution of the Burgers' equation. The initialized IQP model is then adapted on a higher-resolution solution domain. We find that this structured initialization consistently outperforms random latent initialization, yielding improved adaptation behavior and stronger generative accuracy across multiple viscosity settings. These results show that classical surrogate representations can provide useful inductive bias for quantum generative models and offer a practical route to improved initialization in IQP-based learning."
hugoblox:
  ids:
    arxiv: "2607.28866"
links:
  - type: source
    url: https://inspirehep.net/literature/3185164
    label: INSPIRE
featured: false
---
