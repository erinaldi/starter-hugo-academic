---
title: "Learning to Prepare Molecular Ground States with Transformer Models"
authors:
  - Alex Koziell-Pipe
  - Jasmine Brewer
  - Jem Guhit
  - Marwa H. Farag
  - Kripa Panchagnula
  - Gabriel Laude
  - Fabian Finger
  - Carlo Gaggioli
  - Ludmila Szulakowska
  - Oliver J. Backhouse
  - Christos Papalitsas
  - Jason G. Mustakis
  - Thomas Soini
  - David Munoz Ramo
  - Stephen Clark
  - Elica Kyoseva
  - me
date: "2026-07-24"
publication_types:
  - article
abstract: "Quantum state preparation is a key component of many quantum algorithms. Performing this step efficiently is essential for realizing practical quantum advantage in quantum chemistry applications. Iterative algorithms like ADAPT-VQE can produce shallow ground-state preparation circuits, but become computationally prohibitive for the larger molecules relevant to materials science and pharmaceutical development. Here, we introduce ADAPT-GQE, a generative AI framework that learns to synthesize ground-state preparation circuits for electronic structure calculations. We first use ADAPT-VQE to generate high-quality reference circuits, which are then used as targets for training models for circuit generation. Once trained, the model can efficiently propose and score circuits, enabling reinforcement learning (RL) to drive circuit generation accuracy beyond the accuracy of the ADAPT-VQE training data. This pipeline achieves order-of-magnitude reductions in circuit generation time relative to ADAPT-VQE while maintaining comparable or improved state-preparation accuracy. We demonstrate ADAPT-GQE on imipramine, a well-established tricyclic antidepressant that serves as a representative, challenging target for computational modelling in drug stability protocols. We execute generated circuits on Quantinuum Helios-1, representing a milestone for AI-generated quantum chemistry circuits on state-of-the-art quantum hardware. These results establish a pathway toward automated quantum circuit synthesis for utility-scale quantum computational chemistry."
hugoblox:
  ids:
    arxiv: "2607.22468"
links:
  - type: source
    url: https://inspirehep.net/literature/3183310
    label: INSPIRE
featured: false
---
