---
title: "One-way compression function"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/One-way_compression_function"
wikipedia_categories: ["Cryptographic hash functions", "Cryptographic primitives"]
related: ["[[Comparison of cryptographic hash functions]]", "[[Cryptographic hash function]]", "[[Shabal]]", "[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Block cipher]]", "[[Collision attack]]", "[[Conditional disclosure of secrets]]", "[[Crypt (C)]]"]
---

# One-way compression function

In cryptography, a one-way compression function is a function that transforms two fixed-length inputs into a fixed-length output. The transformation is "one-way", meaning that it is difficult given a particular output to compute inputs which compress to that output. One-way compression functions are not related to conventional data compression algorithms, which instead can be inverted exactly (lossless compression) or approximately (lossy compression) to the original data.

One-way compression functions are for instance used in the Merkle–Damgård construction inside cryptographic hash functions.
One-way compression functions are often built from block ciphers.
Some methods to turn any normal block cipher into a one-way compression function are Davies–Meyer, Matyas–Meyer–Oseas, Miyaguchi–Preneel (single-block-length compression functions) and MDC-2/Meyer–Schilling, MDC-4, Hirose (double-block-length compression functions). These methods are described in detail further down. (MDC-2 is also the name of a hash function patented by IBM.)
Another method is 2BOW (or NBOW in general), which is a "high-rate multi-block-length hash function based on block ciphers" and typically achieves (asymptotic) rates between 1 and 2 independent of the hash size (only with small constant overhead). This method has not yet seen any serious security analysis, so should be handled with care.

## Related

- [[Comparison of cryptographic hash functions]]
- [[Cryptographic hash function]]
- [[Shabal]]
- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Block cipher]]
- [[Collision attack]]
- [[Conditional disclosure of secrets]]
- [[Crypt (C)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/One-way_compression_function