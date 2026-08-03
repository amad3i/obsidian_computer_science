---
title: "Rainbow table"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Rainbow_table"
wikipedia_categories: ["Cryptographic attacks", "Cryptographic hash functions", "Hash-based data structures", "Search algorithms"]
related: ["[[Collision attack]]", "[[Universal hashing]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[3-subset meet-in-the-middle attack]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]"]
---

# Rainbow table

A rainbow table is a precomputed table for caching the outputs of a cryptographic hash function, usually for cracking password hashes. Passwords are typically stored not in plain text form, but as hash values. If such a database of hashed passwords falls into the hands of attackers, they can use a precomputed rainbow table to recover the plaintext passwords. A common defense against this attack is to compute the hashes using a key derivation function that adds a "salt" to each password before hashing it, with different passwords receiving different salts, which are stored in plain text along with the hash.
Rainbow tables are a practical example of a space–time tradeoff: they use less computer processing time and more storage than a brute-force attack which calculates a hash on every attempt, but more processing time and less storage than a simple table that stores the hash of every possible password.
Rainbow tables were invented by Philippe Oechslin as an application of an earlier, simpler algorithm by Martin Hellman.

## Related

- [[Collision attack]]
- [[Universal hashing]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[3-subset meet-in-the-middle attack]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rainbow_table