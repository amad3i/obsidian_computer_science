---
title: "S-box"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/S-box"
wikipedia_categories: ["Cryptographic algorithms", "S-box"]
related: ["[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[CryptGenRandom]]", "[[Crypto++]]"]
---

# S-box

In cryptography, an S-box (substitution-box) is a basic component of symmetric key algorithms which performs substitution. In block ciphers, they are typically used to obscure the relationship between the key and the ciphertext, thus ensuring Shannon's property of confusion. Mathematically, an S-box is a nonlinear vectorial Boolean function.
In general, an S-box takes some number of input bits, m, and transforms them into some number of output bits, n, where n is not necessarily equal to m.  An m×n S-box can be implemented as a lookup table with 2m words of n bits each. Fixed tables are normally used, as in the Data Encryption Standard (DES), but in some ciphers the tables are generated dynamically from the key (e.g. the Blowfish and the Twofish encryption algorithms).

## Related

- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[CryptGenRandom]]
- [[Crypto++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/S-box