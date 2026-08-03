---
title: "JH (hash function)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/JH_(hash_function)"
wikipedia_categories: ["Cryptographic hash functions", "Cryptography stubs", "NIST hash function competition"]
related: ["[[Grøstl]]", "[[Ascon (cipher)]]", "[[FORK-256]]", "[[Gimli (cipher)]]", "[[HAIFA construction]]", "[[HAS-160]]", "[[HAS-V]]", "[[HAVAL]]", "[[MD6]]", "[[N-hash]]"]
---

# JH (hash function)

JH is a  cryptographic hash function submitted to the NIST hash function competition by Hongjun Wu. Though chosen as one of the five finalists of the competition, in 2012 JH ultimately lost to NIST hash candidate Keccak. JH has a 1024-bit state, and works on 512-bit input blocks.  Processing an input block consists of three steps:

XOR the input block into the left half of the state.
Apply a 42-round unkeyed permutation (encryption function) to the state.  This consists of 42 repetitions of:
Break the input into 256 4-bit blocks, and map each through one of two 4-bit S-boxes, the choice being made by a 256-bit round-dependent key schedule.  Equivalently, combine each input block with a key bit, and map the result through a 5→4 bit S-box.
Mix adjacent 4-bit blocks using a maximum distance separable code over GF(24).
Permute 4-bit blocks so that they will be adjacent to different blocks in following rounds.
XOR the input block into the right half of the state.
The resulting digest is the last 224, 256, 384 or 512 bits from the 1024-bit final value.
It is well suited to a bit slicing implementation using the SSE2 instruction set, giving speeds of 16.8 cycles per byte.

## Related

- [[Grøstl]]
- [[Ascon (cipher)]]
- [[FORK-256]]
- [[Gimli (cipher)]]
- [[HAIFA construction]]
- [[HAS-160]]
- [[HAS-V]]
- [[HAVAL]]
- [[MD6]]
- [[N-hash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/JH_(hash_function)