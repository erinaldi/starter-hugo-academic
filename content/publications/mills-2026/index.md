---
title: "Reinforcement learning for adaptive composition of quantum circuit optimisation passes"
authors:
  - Daniel Mills
  - Ifan Williams
  - Jacob Swain
  - Gabriel Matos
  - me
  - Alexander Koziell-Pipe
date: "2026-01-29"
publication_types:
  - article-journal
publication: "*Machine Learning: Science and Technology* 7"
abstract: "Many quantum software development kits provide a suite of circuit optimisation passes. These passes have been highly optimised and tested in isolation. However, the order in which they are applied is left to the user, or else defined in general-purpose default pass sequences. While general-purpose sequences miss opportunities for optimisation which are particular to individual circuits, designing pass sequences bespoke to particular circuits requires exceptional knowledge about quantum circuit design and optimisation. Here we propose and demonstrate training a reinforcement learning agent to compose optimisation-pass sequences. In particular the agent's action space consists of passes for two-qubit gate count reduction used in default PyTKET pass sequences. For the circuits in our diverse test set, the (mean, median) fraction of two-qubit gates removed by the agent is $(57.7\\%, \\ 56.7 \\%)$, compared to $(41.8 \\%, \\ 50.0 \\%)$ for the next best default pass sequence. In doing so our model demonstrates the ability to forgo reward to improve the final two-qubit gate count. Our approach clearly separates the problem of designing circuit optimisation passes from the problem of using them optimally in practice. We expect this separation of concerns to facilitate innovations in both areas."
hugoblox:
  ids:
    arxiv: "2601.21629"
    doi: 10.1088/2632-2153/aeb2a2
links:
  - type: source
    url: https://inspirehep.net/literature/3113124
    label: INSPIRE
featured: false
---
