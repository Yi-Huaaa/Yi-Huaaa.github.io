---
title: 'Accelerating Gate Sizing using GPU'
authors:
  - me
  - Nahmsuk Oh
  - Malleswara Gupta Balabhadra Naga Venkata
  - Aditya Shiledar
  - Sudipto Kundu
  - Vishal Khandelwal
  - Tsung-Wei Huang
date: '2025-08-02T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "International European Conference on Parallel and Distributed Computing (Euro-Par) PhD Symposium, Dresden, Germany, 2025"
abstract: |
  Gate sizing is important in VLSI design to optimize performance and meet timing constraints. Multi-core CPU-based approaches have been widely used to speed up the gate sizing algorithm, but their scalability is typically limited to 8–16 threads. To address this limitation, we propose a GPU algorithm to accelerate a time-consuming routine of gate sizing, namely the library cell (libcell) selection process, in an industrial-standard sizer. By leveraging both block- and warp-level parallelism, our algorithm can greatly accelerate the libcell selection time. Experimental results show that our GPU implementations achieve up to 38.13×speedup over a 16-core CPU baseline, while warp-level sizing can further achieve additional 4.77% improvement over block-level sizing.
links:
  - type: pdf
    url: uploads/publications/2025-gate-sizing-paper.pdf
  - type: poster
    url: uploads/publications/2025-gate-sizing-poster.pdf
  - type: slides
    url: uploads/publications/2025-gate-sizing-slides.pdf
---
