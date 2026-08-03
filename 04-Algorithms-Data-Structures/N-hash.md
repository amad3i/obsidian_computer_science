---
title: "N-hash"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/N-hash"
wikipedia_categories: ["Cryptographic hash functions", "Cryptography stubs"]
related: ["[[Ascon (cipher)]]", "[[FORK-256]]", "[[Gimli (cipher)]]", "[[Grøstl]]", "[[HAIFA construction]]", "[[HAS-160]]", "[[HAS-V]]", "[[HAVAL]]", "[[JH (hash function)]]", "[[SM3 (hash function)]]"]
---

# N-hash

In cryptography, N-hash is a cryptographic hash function based on the FEAL round function, and is now considered insecure. It was proposed in 1990 in an article by Miyaguchi, Ohta, and Iwata; weaknesses were published the following year.
N-hash has a 128-bit hash size. A message is divided into 128-bit blocks, and each block is combined with the hash value computed so far using the g compression function. g contains eight rounds, each of which uses an F function, similar to the one used by FEAL.
Eli Biham and Adi Shamir (1991) applied the technique of differential cryptanalysis to N-hash, and showed that collisions could be generated faster than by a birthday attack for N-hash variants with even up to 12 rounds.

## Related

- [[Ascon (cipher)]]
- [[FORK-256]]
- [[Gimli (cipher)]]
- [[Grøstl]]
- [[HAIFA construction]]
- [[HAS-160]]
- [[HAS-V]]
- [[HAVAL]]
- [[JH (hash function)]]
- [[SM3 (hash function)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/N-hash