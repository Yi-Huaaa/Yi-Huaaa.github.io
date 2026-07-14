---
title: 'iG-kway: Incremental k-way Graph Partitioning on GPU'
authors:
  - Wan-Luan Lee
  - Shui Jiang
  - Dian-Lun Lin
  - Che Chang
  - Boyang Zhang
  - me
  - Ulf Schlichtmann
  - Tsung-Yi Ho
  - Tsung-Wei Huang
date: '2025-06-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, 2025"
abstract: |
  Recent advances in GPU-accelerated graph partitioning have achieved significant performance gains but remain limited to full graph partitioning, lacking support for incremental updates. This limitation is critical in CAD applications, where circuit graphs undergo iterative, incremental modifications during optimization. We present iG-kway, the first GPU-based incremental k-way graph partitioner. iG-kway features an incrementality-aware data structure and a refinement kernel that efficiently updates only affected vertices with minimal quality loss. Experiments show that iG-kway delivers up to 84x speedup over the state-of-the-art G-kway with comparable partitioning quality.
links:
  - type: pdf
    url: uploads/publications/2025-igkway.pdf
---
