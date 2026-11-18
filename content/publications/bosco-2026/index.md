---
title: "Efficiently Simulable Pauli Correlation Encoding"
authors:
  - Daniele Lizzio Bosco
  - Gabriel Matos
  - Chen-Yu Liu
  - Frederic Rapp
  - Fabian Finger
  - me
  - Konstantinos Meichanetzidis
date: "2026-07-22"
publication_types:
  - article
abstract: "Pauli Correlation Encoding (PCE) is a heuristic framework for binary optimisation that encodes classical variables into many-body Pauli observables. While PCE requires fewer qubits than other approaches, it relies on estimating a large number of Pauli expectation values whose signs determine the variables' values, which can incur substantial measurement overhead. Here, we introduce efficiently simulable PCE, a class of dequantised PCE realisations where all expectation values needed can be computed efficiently classically. We instantiate this idea using free-fermionic evolutions, realised by matchgate circuits, and Instantaneous Quantum Polynomial (IQP) circuits. On MaxCut, Maximum Independent Set, Multi-Dimensional Knapsack, and Max3SAT benchmarks, these methods produce high-quality solutions across problem sizes ranging from tens to thousands of variables. Our results show that PCE is naturally understood as a correlation-based optimisation framework with both quantum and classically simulable realisations. This yields a dequantised baseline for evaluating future quantum PCE implementations."
hugoblox:
  ids:
    arxiv: "2607.20409"
links:
  - type: source
    url: https://inspirehep.net/literature/3182706
    label: INSPIRE
featured: false
---
