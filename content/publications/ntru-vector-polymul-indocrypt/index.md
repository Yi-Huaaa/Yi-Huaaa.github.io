---
title: 'Algorithmic Views of Vectorized Polynomial Multipliers - NTRU (2023)'
authors:
  - Han-Ting Chen
  - me
  - Vincent Hwang
  - Bo-Yin Yang
date: '2023-01-01T00:00:00Z'
publication_types: ['paper-conference']
publication:
  name: "Indocrypt, 2023"
abstract: |
  The lattice-based post-quantum cryptosystem NTRU is used by Google for protecting Google's internal communication. In NTRU, polynomial multiplication is one of bottleneck. In this paper, we explore the interactions between polynomial multiplications, Toeplitz matrix-vector products, and vectorization with architectural insights. For a unital commutative ring R, a positive integer n, and an element ζ in R, we reveal the benefit of vector-by-scalar multiplication instructions while multiplying in R[x]/(x^n − ζ).

  We aim at designing an algorithm exploiting no algebraic and number-theoretic properties of n and ζ. An obvious way is to multiply in R[x] and reduce modulo x^n − ζ. Since the product in R[x] is a polynomial of degree at most 2n − 2, one usually chooses a polynomial modulus g such that (i) deg(g) ≥ 2n − 1, and (ii) there exists a well-studied fast polynomial multiplication algorithm f for multiplying in R[x]/(g).

  We deviate from common approaches and point out a novel insight with dual modules and vector-by-scalar multiplications. Conceptually, we relate the module-theoretic duals of R[x]/(x^n − ζ) and R[x]/(g) with Toeplitz matrix-vector products, and demonstrate the benefit of Toeplitz matrix-vector products with vector-by-scalar multiplication instructions. It greatly reduces the register pressure, and allows us to multiply with essentially no permutation instructions that are commonly used in vectorized implementation.

  We implement the ideas for the NTRU parameter sets `ntruhps2048677` and `ntruhrss701` on a Cortex-A72 implementing the Armv8.0-A architecture with the single-instruction-multiple-data (SIMD) technology Neon. For polynomial multiplications, our implementation is 2.18x and 2.23x for `ntruhps2048677` and `ntruhrss701` than the state-of-the-art optimized implementation. We also vectorize the polynomial inversions and sorting network by employing existing techniques and translating AVX2-optimized implementations into Neon. Compared to the state-of-the-art optimized implementation, our key generation, encapsulation, and decapsulation for `ntruhps2048677` are 7.67x, 2.48x, and 1.77x faster, respectively. For `ntruhrss701`, our key generation, encapsulation, and decapsulation are 7.99x, 1.47x, and 1.56x faster, respectively.
links:
  - type: pdf
    url: uploads/publications/2023-ntru-indocrypt.pdf
---
