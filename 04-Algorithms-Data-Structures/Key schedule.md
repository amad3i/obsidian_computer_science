---
title: "Key schedule"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Key_schedule"
wikipedia_categories: ["Cryptographic algorithms"]
related: ["[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[CryptGenRandom]]", "[[Crypto++]]"]
---

# Key schedule

In cryptography, the so-called product ciphers are a certain kind of cipher, where the (de-)ciphering of data is typically done as an iteration of rounds.  The setup for each round is generally the same, except for round-specific fixed values called a round constant, and round-specific data derived from the cipher key called a round key.  A key schedule is an algorithm that calculates all the round keys from the key.

## Related

- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[CryptGenRandom]]
- [[Crypto++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Key_schedule