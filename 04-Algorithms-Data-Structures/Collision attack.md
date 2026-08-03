---
title: "Collision attack"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Collision_attack"
wikipedia_categories: ["Cryptographic attacks", "Cryptographic hash functions"]
related: ["[[Rainbow table]]", "[[3-subset meet-in-the-middle attack]]", "[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[CryptoLocker]]", "[[Downgrade attack]]"]
---

# Collision attack

In cryptography, a collision attack on a cryptographic hash tries to find two inputs producing the same hash value, i.e. a hash collision. This is in contrast to a preimage attack where a specific target hash value is specified.
There are roughly two types of collision attacks:

Classical collision attack
Find two different messages m1 and m2 such that hash(m1) = hash(m2).
More generally:

Chosen-prefix collision attack
Given two different prefixes p1 and p2, find two suffixes s1 and s2 such that hash(p1 ∥ s1) = hash(p2 ∥ s2), where ∥ denotes the concatenation operation.

## Related

- [[Rainbow table]]
- [[3-subset meet-in-the-middle attack]]
- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[CryptoLocker]]
- [[Downgrade attack]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Collision_attack