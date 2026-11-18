---
title: "Deep Learning Approaches to Quantum Error Mitigation"
authors:
  - Leonardo Placidi
  - Ifan Williams
  - me
  - Daniel Mills
  - Cristina Cîrstoiu
  - Vanya Eccles
  - Ross Duncan
date: "2026-01-20"
publication_types:
  - article
abstract: "We present a systematic investigation of deep learning methods applied to quantum error mitigation of noisy output probability distributions from measured quantum circuits. We compare different architectures, from fully connected neural networks to transformers, and we test different design/training modalities, identifying sequence-to-sequence, attention-based models as the most effective on our datasets. These models consistently produce mitigated distributions that are closer to the ideal outputs when tested on both simulated and real device data obtained from IBM superconducting quantum processing units (QPU) up to five qubits. Across several different circuit depths, our approach outperforms other baseline error mitigation techniques. We perform a series of ablation studies to examine: how different input features (circuit, device properties, noisy output statistics) affect performance; cross-dataset generalization across circuit families; and transfer learning to a different IBM QPU. We observe that generalization performance across similar devices with the same architecture works effectively, without needing to fully retrain models."
hugoblox:
  ids:
    arxiv: "2601.14226"
links:
  - type: source
    url: https://inspirehep.net/literature/3109588
    label: INSPIRE
featured: false
---
