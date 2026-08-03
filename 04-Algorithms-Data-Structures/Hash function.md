---
title: "Hash function"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Hash_function"
wikipedia_categories: ["Hash functions", "Search algorithms"]
related: ["[[K-independent hashing]]", "[[Perfect hash function]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]"]
---

# Hash function

A hash function is any function that can be used to map data of arbitrary size to fixed-size values, though there are some hash functions that support variable-length output. The values returned by a hash function are called hash values, hash codes, (hash/message) digests, or simply hashes.  The values are usually used to index a fixed-size table called a hash table. Use of a hash function to index a hash table is called hashing or scatter-storage addressing.
Hash functions and their associated hash tables are used in data storage and retrieval applications to access data in a small and nearly constant time per retrieval. They require an amount of storage space only fractionally greater than the total space required for the data or records themselves. Hashing is a way to access data quickly and efficiently. Unlike lists or trees, it provides near-constant access time. It also uses much less storage than trying to store all possible keys directly, especially when keys are large or variable in length.
Use of hash functions relies on statistical properties of key and function interaction: worst-case behavior is intolerably bad but rare, and average-case behavior can be nearly optimal (minimal collision).
Hash functions are related to (and often confused with) checksums, check digits, fingerprints, lossy compression, randomization functions, error-correcting codes, and ciphers. Although the concepts overlap to some extent, each one has its own uses and requirements and is designed and optimized differently. The hash function differs from these concepts mainly in terms of data integrity. Hash tables may use non-cryptographic hash functions, while cryptographic hash functions are used in cybersecurity to secure sensitive data such as passwords.

## Related

- [[K-independent hashing]]
- [[Perfect hash function]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hash_function