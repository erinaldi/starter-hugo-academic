---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-11-18
type: landing

sections:
  - block: resume-biography-3
    content:
      # Author profile to display (file name in `data/authors/`)
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research sits at the interface of theoretical physics and computation. I develop and apply
        **quantum algorithms** for the simulation of quantum many-body systems and quantum field theories,
        with a focus on **lattice gauge theories** and **Hamiltonian simulation** on quantum computers.

        I have a long background in **lattice field theory**: Markov Chain Monte Carlo simulations of
        strongly-coupled gauge theories on supercomputers, applied to composite Higgs and dark matter models,
        low-energy nuclear physics from Quantum Chromodynamics, and matrix models connected to quantum gravity
        through the gauge/gravity duality. I also use **machine learning** to accelerate scientific discovery
        in these areas.

        A complete list of my publications is available on
        [INSPIRE-HEP](https://inspirehep.net/author/profile/E.Rinaldi.1) and
        [Google Scholar](https://scholar.google.com/citations?user=zxraLMsAAAAJ).
    design:
      columns: '1'

  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: ''
      filters:
        folders:
          - publications
        featured_only: true
      count: 6
      order: desc
    design:
      view: citation
      columns: '1'
---
