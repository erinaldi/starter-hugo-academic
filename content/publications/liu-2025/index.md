---
title: "Quantum Relational Knowledge Distillation"
authors:
  - Chen-Yu Liu
  - Kuan-Cheng Chen
  - Keisuke Murota
  - Samuel Yen-Chi Chen
  - me
date: "2025-08-18"
publication_types:
  - article
abstract: "Knowledge distillation (KD) is a widely adopted technique for compressing large models into smaller, more efficient student models that can be deployed on devices with limited computational resources. Among various KD methods, Relational Knowledge Distillation (RKD) improves student performance by aligning relational structures in the feature space, such as pairwise distances and angles. In this work, we propose Quantum Relational Knowledge Distillation (QRKD), which extends RKD by incorporating quantum relational information. Specifically, we map classical features into a Hilbert space, interpret them as quantum states, and compute quantum kernel values to capture richer inter-sample relationships. These quantum-informed relations are then used to guide the distillation process. We evaluate QRKD on both vision and language tasks, including CNNs on MNIST and CIFAR-10, and GPT-2 on WikiText-2, Penn Treebank, and IMDB. Across all benchmarks, QRKD consistently improves student model performance compared to classical RKD. Importantly, both teacher and student models remain classical and deployable on standard hardware, with quantum computation required only during training. This work presents the first demonstration of quantum-enhanced knowledge distillation in a fully classical deployment setting."
hugoblox:
  ids:
    arxiv: "2508.13054"
links:
  - type: source
    url: https://inspirehep.net/literature/2961911
    label: INSPIRE
featured: false
---
