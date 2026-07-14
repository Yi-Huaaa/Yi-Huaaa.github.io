---
title: 'QDP: Worst-case Fidelity-aware Qubit Mapping and Routing using Dynamic Programming'
authors:
  - Shui Jiang
  - Wen Cheng
  - me
  - Tsung-Yi Ho
  - Tsung-Wei Huang
date: '2026-01-02T00:00:00Z'
publication_types: ['article-journal']
publication:
  name: "IEEE Transactions on Computer-aided Design of Integrated Circuits and Systems (TCAD), to appear"
abstract: |
  Qubit mapping and routing (QMR) is a critical step in quantum computing because it maps logical qubits to a physical layout while properly routing all gates. In QMR, achieving high qubit fidelity is essential as it ensures reliable execution of a quantum circuit on a quantum computer. However, existing QMR algorithms focus on optimizing the average fidelity (AVF) across all qubits, ignoring the worst-case fidelity (WCF) of individual qubits. In practice, a particularly low-fidelity qubit can greatly diminish the reliability of a quantum circuit as a single qubit failure can lead to the failure of the entire circuit. To address this issue, we introduce QDP, a parallel dynamic programming (DP)-based QMR algorithm that optimizes the WCF while balancing the overall AVF. QDP leverages a state graph as the optimal substructure for our DP formulation to capture all valid quantum circuit execution orders. To enhance performance, QDP introduces a parallel DP-based state traversal algorithm that maximizes WCF through remapping and reduces the size of the state graph via progressive state expansion. Compared with state-of-the-art QMR algorithms, QDP can enhance the WCF by up to 33.88% while achieving comparable AVF on real quantum computers with up to 53 qubits.
links:
  - type: pdf
    url: uploads/publications/2026-QDP.pdf  
---
