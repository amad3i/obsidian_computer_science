---
title: "Argon2"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Argon2"
wikipedia_categories: ["2015 in computing", "Cryptographic hash functions", "Key derivation functions"]
related: ["[[Bcrypt]]", "[[Crypt (C)]]", "[[Scrypt]]", "[[Yescrypt]]", "[[Ascon (cipher)]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]"]
---

# Argon2

Argon2 is a key derivation function that was selected as the winner of the 2015 Password Hashing Competition. It was designed by Alex Biryukov, Daniel Dinu, and Dmitry Khovratovich from the University of Luxembourg. The reference implementation of Argon2 is released under a Creative Commons CC0 license (i.e. public domain) or the Apache License 2.0.
The Argon2 function uses a large, fixed-size memory region (often called the 'memory array' in documentation) to make brute-force attacks computationally expensive. The three variants differ in how they access this memory:

Argon2d maximizes resistance to GPU cracking attacks. It accesses the memory array in a password-dependent order, which reduces the possibility of time–memory trade-off (TMTO) attacks, but introduces possible side-channel attacks.
Argon2i is optimized to resist side-channel attacks. It accesses the memory array in a password-independent order.
Argon2id is a hybrid version. It follows the Argon2i approach for the first half pass over memory and the Argon2d approach for subsequent passes. RFC 9106 recommends using Argon2id if one does not know the difference between the types or if side-channel attacks are considered to be a viable threat.
All three modes allow specification by three parameters that control:

execution time
memory required
degree of parallelism

## Related

- [[Bcrypt]]
- [[Crypt (C)]]
- [[Scrypt]]
- [[Yescrypt]]
- [[Ascon (cipher)]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]
- [[Fast syndrome-based hash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Argon2