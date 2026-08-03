---
title: "Elliptic curve only hash"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Elliptic_curve_only_hash"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]", "[[Gimli (cipher)]]"]
---

# Elliptic curve only hash

The elliptic curve only hash (ECOH) algorithm was submitted as a candidate for SHA-3 in the NIST hash function competition. However, it was rejected in the beginning of the competition since a second pre-image attack was found.
The ECOH is based on the MuHASH hash algorithm, that has not yet been successfully attacked. However, MuHASH is too inefficient for practical use and changes had to be made. The main difference is that where MuHASH applies a random oracle , ECOH applies a padding function. Assuming random oracles, finding a collision in MuHASH implies solving the discrete logarithm problem. MuHASH is thus a provably secure hash, i.e. we know that finding a collision is at least as hard as some hard known mathematical problem.
ECOH does not use random oracles and its security is not strictly directly related to the discrete logarithm problem, yet it is still based on mathematical functions. ECOH is related to the Semaev's problem of finding low degree solutions to the summation polynomial equations over binary field, called the Summation Polynomial Problem. An efficient algorithm to solve this problem has not been given so far. Although the problem was not proven to be NP-hard, it is assumed that such an algorithm does not exist. Under certain assumptions, finding a collision in ECOH may be also viewed as an instance of the subset sum problem. Besides solving the Summation Polynomial Problem, there exists another way how to find second pre-images and thus collisions, Wagner's generalized birthday attack.
ECOH is a good example of hash function that is based on mathematical functions (with the provable security approach) rather than on classical ad hoc mixing of bits to obtain the hash.

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Fast syndrome-based hash]]
- [[FORK-256]]
- [[Gimli (cipher)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Elliptic_curve_only_hash