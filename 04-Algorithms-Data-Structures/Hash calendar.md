---
title: "Hash calendar"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Hash_calendar"
wikipedia_categories: ["Cryptographic hash functions", "Error detection and correction", "Hashing", "Trees (data structures)"]
related: ["[[Merkle tree]]", "[[Hash list]]", "[[Comparison of cryptographic hash functions]]", "[[Cryptographic hash function]]", "[[Puzzle friendliness]]", "[[Shabal]]", "[[Universal hashing]]", "[[Abstract syntax tree]]", "[[Acknowledgement (data networks)]]", "[[Alternant code]]"]
---

# Hash calendar

A hash calendar is a data structure that is used to measure the passage of time by adding hash values to an append-only database with one hash value per elapsed second. It can be thought of special kind of Merkle or hash tree, with the property that at any given moment, the tree contains a leaf node for each second since 1970‑01‑01 00:00:00 UTC.

The leaves are numbered left to right starting from zero and new leaves are always added to the right. By periodically publishing the root of the hash-tree is it possible to use a hash calendar as the basis of a hash-linking based digital timestamping scheme.

## Related

- [[Merkle tree]]
- [[Hash list]]
- [[Comparison of cryptographic hash functions]]
- [[Cryptographic hash function]]
- [[Puzzle friendliness]]
- [[Shabal]]
- [[Universal hashing]]
- [[Abstract syntax tree]]
- [[Acknowledgement (data networks)]]
- [[Alternant code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hash_calendar