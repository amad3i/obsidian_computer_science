---
title: "Very smooth hash"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Very_smooth_hash"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# Very smooth hash

In cryptography, Very Smooth Hash (VSH) is a provably secure cryptographic hash function invented in 2005 by Scott Contini, Arjen Lenstra, and Ron Steinfeld. Provably secure means that finding collisions is as difficult as some known hard mathematical problem. Unlike other provably secure collision-resistant hashes, VSH is efficient and usable in practice. Asymptotically, it only requires a single multiplication per log(n) message-bits and uses RSA-type arithmetic. Therefore, VSH can be useful in embedded environments where code space is limited.
Two major variants of VSH were proposed. For one, finding a collision is provably as difficult as finding a nontrivial modular square root of a very smooth number modulo n. The other one uses a prime modulus p (with no trapdoor), and its security proof relies on the hardness of finding discrete logarithms of very smooth numbers modulo p. Both versions have similar efficiency.
VSH is not suitable as a substitute for a random oracle, but can be used to build a provably secure randomized trapdoor hash function. This function can replace the trapdoor function used in the Cramer–Shoup signature scheme, maintaining its provable security while speeding up verification time by about 50%.

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

- Wikipedia: https://en.wikipedia.org/wiki/Very_smooth_hash