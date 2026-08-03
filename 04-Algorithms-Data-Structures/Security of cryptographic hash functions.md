---
title: "Security of cryptographic hash functions"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Security_of_cryptographic_hash_functions"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# Security of cryptographic hash functions

In cryptography, cryptographic hash functions can be divided into two main categories. In the first category are those functions whose designs are based on mathematical problems, and whose security thus follows from rigorous mathematical proofs, complexity theory and formal reduction. These functions are called provably secure cryptographic hash functions. To construct these is very difficult, and few examples have been introduced. Their practical use is limited.
In the second category are functions which are not based on mathematical problems, but on an ad-hoc constructions, in which the bits of the message are mixed to produce the hash. These are then believed to be hard to break, but no formal proof is given. Almost all hash functions in widespread use reside in this category. Some of these functions are already broken, and are no longer in use. See Hash function security summary.

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

- Wikipedia: https://en.wikipedia.org/wiki/Security_of_cryptographic_hash_functions