---
title: "Unbiased Hamiltonian Simulation by Reversing Trotter Error Dynamics"
authors:
  - Keisuke Murota
  - Yuta Kikuchi
  - me
  - Frédéric Sauvage
  - Synge Todo
date: "2026-06-29"
publication_types:
  - article
abstract: "Owing to their simplicity and low overhead, Suzuki-Trotter formulas remain the de facto Hamiltonian simulation methods on current quantum computing platforms. Systematic Trotter errors, however, will quickly become limiting when scaling to larger problems and aiming for higher accuracy. We present a mechanism that removes the systematic error of any $k$-th order Suzuki-Trotter simulation, at the cost of a constant sampling overhead. The key insight is that the Trotter error is itself a coherent dynamics to be reversed, rather than a deviation to be bounded. By identifying the structure of this error in closed form, we carry out that reversal through quasi-probabilistic decompositions. The resulting algorithm, called Probabilistic Trotter Error Reversal (PTER), is unbiased and still improves the gate-count scaling of Suzuki-Trotter formulas while retaining their simplicity. Numerical simulations of a Heisenberg spin chain support the predicted resource advantage already at modest system sizes."
hugoblox:
  ids:
    arxiv: "2606.29741"
links:
  - type: source
    url: https://inspirehep.net/literature/3174730
    label: INSPIRE
featured: false
---
