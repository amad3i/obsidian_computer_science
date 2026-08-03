---
title: "Montgomery modular multiplication"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Montgomery_modular_multiplication"
wikipedia_categories: ["Computer arithmetic", "Cryptographic algorithms", "Modular arithmetic"]
related: ["[[Kochanski multiplication]]", "[[Modular exponentiation]]", "[[2Sum]]", "[[Arithmetic logic unit]]", "[[Automorphic number]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]"]
---

# Montgomery modular multiplication

In modular arithmetic computation, Montgomery modular multiplication, more commonly referred to as Montgomery multiplication, is a method for performing fast modular multiplication.  It was introduced in 1985 by the American mathematician Peter L. Montgomery.
Montgomery modular multiplication relies on a special representation of numbers called Montgomery form. The algorithm uses the Montgomery forms of a and b to efficiently compute the Montgomery form of ab mod N. The efficiency comes from avoiding expensive division operations. Classical modular multiplication reduces the double-width product ab using division by N and keeping only the remainder. This division requires quotient digit estimation and correction. The Montgomery form, in contrast, depends on a constant R > N which is coprime to N, and the only division necessary in Montgomery multiplication is division by R. The constant R can be chosen so that division by R is easy, significantly improving the speed of the algorithm.  In binary computers, R is always a power of two, since division by powers of two can be implemented by bit shifting.
The need to convert a and b into Montgomery form and their product out of Montgomery form means that computing a single product by Montgomery multiplication is slower than the conventional or Barrett reduction algorithms.  However, when performing many multiplications in a row, as in modular exponentiation, intermediate results can be left in Montgomery form. Then the initial and final conversions become a negligible fraction of the overall computation.  Many important cryptosystems such as RSA and Diffie–Hellman key exchange are based on arithmetic operations modulo a large odd number, and for these cryptosystems, computations using Montgomery multiplication with R a power of two are faster than the available alternatives.

## Related

- [[Kochanski multiplication]]
- [[Modular exponentiation]]
- [[2Sum]]
- [[Arithmetic logic unit]]
- [[Automorphic number]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Montgomery_modular_multiplication