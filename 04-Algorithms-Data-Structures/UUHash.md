---
title: "UUHash"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/UUHash"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# UUHash

UUHash is a hash algorithm employed by clients on the FastTrack network. It is employed for its ability to hash very large files in a very short period of time, even on older computers. However, this is achieved by only hashing a fraction of the file. This weakness makes it trivial to create a hash collision, allowing large sections to be completely altered without altering the checksum.
This method is used by Kazaa. The weakness of UUHash is exploited by anti-p2p agencies to corrupt downloads.

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

- Wikipedia: https://en.wikipedia.org/wiki/UUHash