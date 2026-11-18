---
title: "Simulating the dynamics of an SU(2) matrix model on a trapped-ion quantum computer"
authors:
  - Gavin S. Hartnett
  - Haoran Liao
  - me
date: "2026-04-15"
publication_types:
  - article
abstract: "Matrix models are an important class of systems in string theory and theoretical physics, with applications to random matrix theory, quantum chaos, and black holes. Hamiltonian Monte Carlo simulations and gauge/gravity duality have been used to study these systems at thermal equilibrium, and the bootstrap program has been used to efficiently determine operator expectation values by imposing positivity constraints. However, simulating real-time, non-equilibrium dynamics remains a fundamental challenge. In this work, we present the first digital quantum simulation of a bosonic matrix model, executed on the Quantinuum System Model H2 trapped-ion quantum computer. We focus on an $\\mathrm{SU}(2)$ gauge theory with a quartic potential as it is simple enough to validate against exact classical solutions and yet complex enough to reflect the non-local structure of larger theories. Using the Loschmidt echo as our primary dynamical observable, we systematically decompose simulation errors into three distinct sources: Hilbert space truncation, Trotterization, and hardware noise. We demonstrate a new post-selection scheme that detects and discards gauge-symmetry violations in the Fock basis and show that at small scales it, along with zero-noise extrapolation, can give modest improvements in fidelity. These approaches struggle to scale to larger system sizes in their current implementations, emphasizing the need to move beyond them and to focus on depth reduction through improved compilation and unitary synthesis, and run-time error handling such as additional error suppression, error detection, as well as error correction approaches. This work establishes a foundation for extending digital quantum simulation to more complex matrix models -- revealing that fundamental challenges in qubit resources and circuit depth remain formidable obstacles for scaling to holographically interesting regimes."
hugoblox:
  ids:
    arxiv: "2604.14094"
links:
  - type: source
    url: https://inspirehep.net/literature/3145528
    label: INSPIRE
featured: false
---
