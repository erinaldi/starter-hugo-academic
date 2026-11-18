---
title: Simulating the Weak Death of the Neutron in a Femtoscale Universe with Near-Exascale Computing
authors:
  - Evan Berkowitz
  - M.A. Clark
  - Arjun Gambhir
  - Ken McElvain
  - Amy Nicholson
  - me
  - Pavlos Vranas
  - Andre Walker-Loud
  - Chia Cheng Chang
  - Balint Joo
  - Thorsten Kurth
  - Kostas Orginos
date: '2018-11-01'
featured: false
publishDate: '2021-11-05T00:37:01.601362Z'
publication_types:
  - paper-conference
abstract: The fundamental particle theory called Quantum Chromodynamics (QCD) dictates everything about protons and neutrons, from their intrinsic properties to interactions that bind them into atomic nuclei. Quantities that cannot be fully resolved through experiment, such as the neutron lifetime (whose precise value is important for the existence of light-atomic elements that make the sun shine and life possible), may be understood through numerical solutions to QCD. We directly solve QCD using Lattice Gauge Theory and calculate nuclear observables such as neutron lifetime. We have developed an improved algorithm that expoentially decreases the time-to-solution and applied it on the new CORAL supercomputers, Sierra and Summit. We use run-time autotuning to distribute GPU resources, achieving 20% performance at low node count. We also developed optimal application mapping through a job manager, which allows CPU and GPU jobs to be interleaved, yielding 15% of peak performance when deployed across large fractions of CORAL.
publication: '*SC18: International Conference for High Performance Computing, Networking, Storage and Analysis*'
hugoblox:
  ids:
    doi: 10.1109/SC.2018.00058
---
