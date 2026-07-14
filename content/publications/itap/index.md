---
title: 'iTAP: An Incremental Task Graph Partitioner for Task-parallel Static Timing Analysis'
authors:
  - Boyang Zhang
  - Che Chang
  - Cheng-Hsiang Chiu
  - Dian-Lun Lin
  - Yang Sui
  - Chih-Chun Chang
  - me
  - Wan-Luan Lee
  - Zizheng Guo
  - Yibo Lin
  - Tsung-Wei Huang
date: '2025-01-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), Tokyo, Japan, 2025"
abstract: |
  Recent static timing analysis (STA) tools have utilized task dependency graph (TDG) parallelism to enhance the STA runtime performance. Although TDG parallelism shows promising speedup, the overhead of scheduling a TDG can become dominant as the TDG becomes larger. To minimize the scheduling overhead, several TDG partitioning algorithms have been proposed to reduce the TDG size without affecting its task parallelism. Despite improved performance, existing TDG partitioners all fall short of incremental partitioning, limiting their practical use in STA tools that support timing-driven operations. To overcome this limitation, we propose iTAP, an incremental TDG partitioner to fully leverage the power of TDG partitioning in task-parallel STA applications. Compared to a state-of-the-art full TDG partitioner, iTAP enhances the overall STA performance by up to 2.97x.
links:
  - type: pdf
    url: uploads/publications/2025-iTAP.pdf
---
