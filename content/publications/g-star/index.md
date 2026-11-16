---
title: 'G-STAR: GPU-Accelerated Statistical Static Timing Analysis using Level-by-level Replication'
authors:
  - Boyang Zhang
  - Chih-Chun Chang
  - me
  - Che Chang
  - Cheng-Hsiang Chiu
  - Aditya Das Sarma
  - Tsung-Wei Huang
date: '2026-06-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "International European Conference on Parallel and Distributed Computing (Euro-Par), Pisa, Italy, 2026"
abstract: |
  Statistical static timing analysis (SSTA) is a critical component of modern Electronic Design Automation (EDA) flows for modeling on-chip process variations. Among various SSTA methods, first-order block-based SSTA (FB-SSTA) supports efficient level-by-level timing propagation with high data parallelism, making it particularly suitable for GPU acceleration. However, existing GPU-based FB-SSTA solutions assume that the entire timing graph and data fit in GPU memory, an assumption that breaks down as circuit size increases. To overcome this challenge, we propose G-STAR, a GPU-accelerated FB-SSTA algorithm designed for memory-constrained FB-SSTA workloads. G-STAR enables efficient levelized FB-SSTA via level-by-level replication, combined with a replicated-pin scheduler that reuses GPU memory and avoids redundant phase propagation. Compared to a state-of-the-art GPU solution, G-STAR achieves up to 9.24× speedup on large designs and successfully completes FB-SSTA on multi-million-pin circuits where the baseline fails due to GPU out-of-memory errors.
links:
  - type: pdf
    url: uploads/publications/2026-g-star.pdf
---
