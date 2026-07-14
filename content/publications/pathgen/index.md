---
title: 'PathGen: An Efficient Parallel Critical Path Generation Algorithm'
authors:
  - Che Chang
  - Boyang Zhang
  - Cheng-Hsiang Chiu
  - Dian-Lun Lin
  - me
  - Wan-Luan Lee
  - Zizheng Guo
  - Yibo Lin
  - Tsung-Wei Huang
date: '2025-01-02T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), Tokyo, Japan, 2025"
abstract: |
  Critical Path Generation (CPG) is fundamental for many static timing analysis (STA) applications. As the circuit complexity continues to increase, CPG runtime has quickly become the bottleneck due to its time-consuming and iterative nature. Despite many CPG algorithms introduced by existing timers, nearly all of them are limited to a single CPU thread, leading to long runtime for large CPG queries. To mitigate this runtime challenge, we need a parallel CPG algorithm. However, designing a parallel CPG algorithm is very challenging because we need to strategically partition the path search space into multiple groups that can run in parallel while accommodating different slack priorities. To overcome this challenge, we propose PathGen, an efficient CPU-parallel CPG algorithm. PathGen introduces a multi-level queue scheduling framework that can efficiently parallelize the search process of critical paths. Compared to a state-of-the-art single-threaded timer, PathGen is up to 7.4x faster with 16 threads and achieves nearly 100% accuracy when generating one million critical paths on large designs.
links:
  - type: pdf
    url: uploads/publications/2025-PathGen.pdf
---
