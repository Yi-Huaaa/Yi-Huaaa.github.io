---
title: 'SSTA-X: GPU-Accelerated First-Order Block-Based Statistical Static Timing Analysis'
authors:
  - Chih-Chun Chang
  - me
  - Wan-Luan Lee
  - Boyang Zhang
  - Tsung-Wei Huang
date: '2026-01-01T00:00:00Z'
publication_types: ['article-journal']
publication:
  name: "IEEE Transactions on Computer-aided Design of Integrated Circuits and Systems (TCAD), to appear"
abstract: |
  Statistical static timing analysis (SSTA) is a widely used approach to evaluate circuit timing by modeling gate and path delays as random variables affected by process variations. While Monte Carlo-based SSTA methods offer high accuracy, their reliance on massive sampling leads to very long runtime. To alleviate this runtime overhead, first-order block-based SSTA (FB-SSTA) has been proposed to approximate timing distributions through linear propagation of statistical moments. However, existing FB-SSTA solutions are largely limited to CPU-based parallelism, and their scalability can no longer quickly respond to the ever-growing size of SSTA problems. To overcome this limitation, we propose SSTA-X, a GPU-accelerated FB-SSTA algorithm that significantly enhances the runtime performance by leveraging the massive parallelism of modern GPU. SSTA-X introduces GPU-efficient data structures and kernel algorithms to accelerate key yet time-consuming operations in statistical delay, slew, and moment propagation. Experimental results show that SSTA-X achieves 3.10x–12.47x speedup over a CPU-based baseline on a large-scale design with millions of gates.
links:
  - type: pdf
    url: uploads/publications/2026-ssta-x.pdf
---
