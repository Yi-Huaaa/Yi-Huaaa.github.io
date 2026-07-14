---
title: 'A Task-parallel Pipeline Programming Model with Token Dependency'
authors:
  - Cheng-Hsiang Chiu
  - Wan-Luan Lee
  - Boyang Zhang
  - me
  - Che Chang
  - Tsung-Wei Huang
date: '2025-05-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "Workshop on Asynchronous Many-Task Systems and Applications (WAMTA), St. Louis, MO, 2025"
abstract: |
  Task-parallel pipeline framework explores pipeline parallelism in applications and is critical in many parallel and heterogeneous areas, such as VLSI static timing analysis and data similarity search. However, existing solutions only deal with certain types of applications in which data dependency exists between preceding data and succeeding data in a forward direction. Some applications, such as video encoding, exhibit data dependency in both forward and backward directions and cannot be processed with existing solutions. To address the limitation, we introduce a token dependency-aware pipeline framework. Our framework associates each data element with a token as its identifier, supports explicit definitions of forward and backward token dependency with an expressive programming model, resolves token dependency using simple data structures, and schedules tokens with lightweight atomic counters. We have evaluated the framework on applications that exhibit both forward and backward token dependency. For example, our framework is 8.6% faster than PARSEC’s implementation in x.264 video encoding applications.
links:
  - type: pdf
    url: uploads/publications/2025-token-dependency-pipeline.pdf  
---
