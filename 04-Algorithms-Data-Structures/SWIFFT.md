---
title: "SWIFFT"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/SWIFFT"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# SWIFFT

In cryptography, SWIFFT is a collection of provably secure hash functions. It is based on the concept of the fast Fourier transform (FFT). SWIFFT is not the first hash function based on the FFT, but it sets itself apart by providing a mathematical proof of its security. It can be shown that finding collisions in SWIFFT is at least as difficult as finding short vectors in cyclic/ideal lattices in the worst case. By giving a security reduction to the worst case of a difficult mathematical problem, SWIFFT gives a much stronger security guarantee than most other cryptographic hash functions.
Unlike many other provably secure hash functions, the algorithm is quite fast, yielding a throughput of 40 Mbit/s on a 3.2 GHz Intel Pentium 4. Although SWIFFT satisfies many desirable cryptographic and statistical properties, it was not designed to be an "all-purpose" cryptographic hash function. For example, it is not a pseudorandom function, and would not be a suitable instantiation of a random oracle. The algorithm is less efficient than most traditional hash functions that do not give a proof of their collision-resistance. Therefore, its practical use would lie mostly in applications where the proof of collision-resistance is particularly valuable, such as digital signatures that must remain trustworthy for a long time.
A modification of SWIFFT called SWIFFTX was proposed as a candidate for SHA-3 function to the NIST hash function competition and was rejected in the first round.

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]
- [[Fast syndrome-based hash]]
- [[FORK-256]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SWIFFT