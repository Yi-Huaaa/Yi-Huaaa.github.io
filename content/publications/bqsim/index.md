---
title: 'BQSim: GPU-accelerated Batch Quantum Circuit Simulation using Decision Diagram'
authors:
  - Shui Jiang
  - me
  - Chih-Chun Chang
  - Tsung-Yi Ho
  - Tsung-Wei Huang
date: '2025-03-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), Rotterdam, Netherlands, 2025"
abstract: |
  Quantum circuit simulation (QCS) plays an important role in the designs and analysis of a quantum algorithm, as it assists researchers in understanding how quantum operations work without accessing expensive quantum computers. Despite many QCS methods, they are largely limited to simulating one input at a time. However, many simulation-driven quantum computing applications, such as testing and verification, require simulating multiple inputs to reason a quantum algorithm under different scenarios. We refer to this type of QCS as batch quantum circuit simulation (BQCS). In this paper, we present BQSim, a GPU-accelerated batch quantum circuit simulator. BQSim is inspired by the state-of-the-art decision diagram (DD) that can compactly represent quantum gate matrices, but overcomes its limitation of CPU-centric simulation. Specifically, BQSim uses DD to optimize a quantum circuit for reduced BQCS computation and converts DD to a GPU-efficient data structure. Additionally, BQSim employs a task graph-based execution strategy to minimize repetitive kernel call overhead and efficiently overlap kernel execution with data movement. Compared with three state-of-the-art quantum circuit simulators, cuQuantum, Qiskit Aer, and FlatDD, BQSim is 3.25x, 159.06x, and 311.42xfaster on average.
links:
  - type: pdf
    url: uploads/publications/2025-bqsim.pdf  
---
