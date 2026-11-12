---
title: 'XEG: A GPU-Parallel Algorithm for Efficient and Effective E-Graph Extraction'
authors:
  - me
  - Hao-Hsiang Hsiao
  - Cheng-Hsiang Chiu
  - Boyang Zhang
  - Che Chang
  - Joshua San Miguel
  - Tsung-Wei Huang
date: '2027-01-01T00:00:00Z'
publishDate: '2026-09-27T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), Heraklion, Crete, Greece, 2027"
abstract: |
  Equality saturation is a promising compiler optimization approach that addresses the phase-ordering problem by compactly representing equivalent programs in an e-graph. However, extracting the optimal program from a saturated e-graph, known as e-graph extraction, is very time-consuming as the e-graph becomes dense and large. In this paper, we present XEG, a GPU-parallel e-graph extractor that achieves both fast runtime and high solution quality. Specifically, XEG introduces efficient algorithms to establish the e-graph and solution space on GPU and leverages ILP to extract a high-quality solution. Experimental results show that XEG (GPU-based) achieves a 243× average speedup over SmoothE (GPU-based) while improving solution quality by 7%. Compared with e-boost (CPU-based), XEG achieves a 7.73× average speedup while maintaining comparable solution quality. In addition, XEG can operate without ILP as a standalone extractor, achieving a 123× average speedup over egg (CPU-based) with comparable solution quality.
links:
  - type: pdf
    url: uploads/publications/2027-xeg-paper.pdf
  # Code not released yet: no url = shown as "Code · Coming soon". Add the repo url when it is public.
  - type: code
---
