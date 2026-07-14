---
title: 'SimPart: A Simple Yet Effective Replication-aided Partitioning Algorithm for Logic Simulation on GPU'
authors:
  - me
  - Shui Jiang
  - Wan Luan Lee
  - Yanqing Zhang
  - Haoxing Ren
  - Tsung-Yi Ho
  - Tsung-Wei Huang
date: '2025-08-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "International European Conference on Parallel and Distributed Computing (Euro-Par), Dresden, Germany, 2025"
abstract: |
  Replication-aided partitioning (RAP) has recently been introduced to facilitate the design of parallel logic simulation algorithms. By replicating overlapped work, RAP can significantly reduce the cost of inter-thread synchronization. However, the state-of-the-art RAP algorithm, RepCut, relies on time-consuming hypergraph construction and partitioning, where minimizing cut size corresponds to reducing replication. To overcome this runtime challenge, we introduce SimPart, a simple yet highly eﬀective and eﬃcient GPU-parallel replication-aided p artitioner. SimPart tackles the partitioning problem directly without solving another proxy problem and proposes a hybrid strategy that can maximally utilize GPU threads for simulation atop our partitions. Compared to RepCut, SimPart achieves an average speedup of 23x in partitioning and 1.58x in GPU-parallel simulation, while increasing the original graph size by only 0.3%.
links:
  - type: pdf
    url: uploads/publications/2025-simpart-paper.pdf
  - type: slides
    url: uploads/publications/2025-simpart-slides.pdf
---
