---
title: 'G-PathGen: An Efficient GPU-Parallel k-Critical Path Generation Algorithm'
authors:
  - Che Chang
  - me
  - Cheng-Hsiang Chiu
  - Wan-Luan Lee
  - Boyang Zhang
  - Ulf Schlichtmann
  - Ing-Chao Lin
  - Xiangyao Yu
  - Tsung-Wei Huang
date: '2026-06-02T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "ACM International Conference on Supercomputing (ICS), Belfast, Northern Ireland, UK, 2026"
abstract: |
  Critical path generation (CPG) plays a key role in many circuit timing analysis (CTA) applications. As the design complexity continues to increase, CPG runtime has become a major bottleneck in many timing-driven applications. To mitigate this runtime challenge, several CPU-based algorithms have been introduced by both the CTA and parallel computing communities, but they remain slow for large CPG problems. While GPU-accelerated solutions exist, they are often inexact and incur significant overhead from iterative CPU–GPU data transfers, limiting their practical use in CTA applications. To overcome this challenge, we propose G-PathGen, an exact GPU-parallel CPG algorithm targeting CTA applications. G-PathGen introduces efficient kernel algorithms for generating critical paths in parallel and dynamically adjusts the generated path count to maximize GPU utilization while minimizing redundant work. Compared to a state-of-the-art GPU solution, G-PathGen is 1.6x–243.8xfaster when generating one million critical paths on industrial circuit graphs.
links:
  - type: pdf
    url: uploads/publications/2026-G-PathGen.pdf
---
