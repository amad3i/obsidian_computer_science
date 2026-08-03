---
title: "Universal one-way hash function"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Universal_one-way_hash_function"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# Universal one-way hash function

In cryptography a universal one-way hash function (UOWHF, often pronounced "woof") is a type of universal hash function of particular importance to cryptography. UOWHFs are proposed as an alternative to collision-resistant hash functions (CRHFs). CRHFs have a strong collision-resistance property: that it is hard, given randomly chosen hash function parameters, to find any collision of the hash function. In contrast, UOWHFs require that it be hard to find a collision where one preimage is chosen independently of the hash function parameters.  The primitive was suggested by Moni Naor and Moti Yung and is also known as "target collision resistant" hash functions; it was employed to construct general digital signature schemes without trapdoor functions, and also within chosen-ciphertext secure public key encryption schemes.
The UOWHF family contains a finite number of hash functions with each 
having the same probability of being used.

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

- Wikipedia: https://en.wikipedia.org/wiki/Universal_one-way_hash_function