---
title: 'Algorithmic Views of Vectorized Polynomial Multipliers for NTRU and NTRU Prime (Long Paper)'
authors:
  - Han-Ting Chen
  - me
  - Vincent Hwang
  - Chi-Ting Liu
  - Bo-Yin Yang
date: '2023-01-02T00:00:00Z'
publication_types: ['manuscript']
publication:
  name: "Cryptology ePrint Archive, Paper 2023/541, 2023"
abstract: |
  This paper explores the design space of vector-optimized polynomial multiplications in the lattice-based key-encapsulation mechanisms NTRU and NTRU Prime. Since NTRU and NTRU Prime do not support straightforward applications of number– theoretic transforms, the state-of-the-art vector code either resorted to Toom–Cook, or introduced various techniques for coefficient ring extensions. All these techniques lead to a large number of small-degree polynomial multiplications, which is the bottleneck in our experiments. For NTRU Prime, we show how to reduce the number of small-degree polynomial multiplications to nearly 1/4 times compared to the previous vectorized code with the same functionality. Our transformations are based on careful choices of FFTs, including Good–Thomas, Rader’s, Schönhage’s, and Bruun’s FFTs. For NTRU, we show how to deploy Toom-5 with 3-bit losses. Furthermore, we show that the Toeplitz matrix–vector product naturally translates into efficient implementations with vector-by-scalar multiplication instructions which do not appear in all prior vector-optimized implementations. We choose the ARM Cortex-A72 CPU which implements the Armv8-A architecture for experiments, because of its wide uses in smartphones, and also the Neon vector instruction set implementing vector-by-scalar multiplications that do not appear in most other vector instruction sets like Intel’s AVX2. Even for platforms without vector-by-scalar multiplications, we expect significant improvements compared to the state of the art, since our transformations reduce the number of multiplication instructions by a large margin. Compared to the state-of-the-art optimized implementations, we achieve 2.18x and 6.7x faster polynomial multiplications for NTRU and NTRU Prime, respectively. For full schemes, we additionally vectorize the polynomial inversions, sorting network, and encoding/decoding subroutines in NTRU and NTRU Prime. For ntruhps2048677, we achieve 7.67x, 2.48x, and 1.77x faster key generation, encapsulation, and decapsulation, respectively. For ntrulpr761, we achieve 3x, 2.87x, and 3.25x faster key generation, encapsulation, and decapsulation, respectively. For sntrup761, there are no previously optimized implementations and we significantly outperform the reference implementation.
links:
  - type: pdf
    url: uploads/publications/2023-ntru-ntrup-long.pdf
  - type: code
    url: https://github.com/vector-polymul-ntru-ntrup/vector-polymul-ntru-ntrup
---