---
title: 'Accelerating Simulated Quantum Annealing with GPU and Tensor Cores'
authors:
  - me
  - Cheng-Jhih Shih
  - Shih-Hao Hung
date: '2022-01-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "International Conference on High Performance Computing, pp. 174-191, Springer, 2022"
abstract: |
  Inspired by quantum annealing, simulated quantum annealing (SQA) mimics quantum tunneling effects on classical computers to perform annealing through a path-integral Monte Carlo simulation, which increases the potential to find the global optima faster than traditional annealing algorithms for large-size combinatorial optimization problems while today’s quantum annealing systems are of a limited number of qubits. As previous studies have accelerated SQA with Graphics Processing Unit (GPU) and specialized hardware such as Field Programmable Gate Array (FPGA), we propose an innovative parallelizing strategy called hierarchical update to vastly improve the efficiency of parallel computing, which is capable of accelerating state-of-the-art SQA implementations further by 7x-47.2x based on our case studies. Furthermore, we develop a tensorizing scheme to leverage the Tensor Cores on modern GPUs to deliver up to 1.83x of additional speedup. Overall, our work solves fully-connected Ising models faster than any previous SQA work. Our solution outperforms existing GPU-based solutions by 86.6x and FPGA-based solutions by 14x.
links:
  - type: pdf
    url: uploads/publications/2022-sqa-gpu-tensor-cores.pdf
  - type: slides
    url: uploads/publications/2022-sqa-gpu-tensor-cores-slides.pdf
---
