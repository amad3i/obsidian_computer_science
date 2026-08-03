---
title: "SHA-2"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/SHA-2"
wikipedia_categories: ["Checksum algorithms", "Cryptographic hash functions", "National Institute of Standards and Technology", "National Security Agency cryptography", "Public-domain software with source code"]
related: ["[[SHA-1]]", "[[Message Authenticator Algorithm]]", "[[NIST hash function competition]]", "[[SHA-3]]", "[[Skein (hash function)]]", "[[SM3 (hash function)]]", "[[Abramowitz and Stegun]]", "[[Advanced Encryption Standard]]", "[[Argon2]]", "[[Ascon (cipher)]]"]
---

# SHA-2

SHA-2 (Secure Hash Algorithm 2) is a set of cryptographic hash functions designed by the United States National Security Agency (NSA) and first published in 2001. They are built using the Merkle–Damgård construction, from a one-way compression function itself built using the Davies–Meyer structure from a specialized block cipher.
SHA-2 includes significant changes from its predecessor, SHA-1. The SHA-2 family consists of six hash functions with digests (hash values) that are 224, 256, 384 or 512 bits: SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256. SHA-256 and SHA-512 are hash functions whose digests are eight 32-bit and 64-bit words, respectively. They use different shift amounts and additive constants, but their structures are otherwise virtually identical, differing only in the number of rounds. SHA-224 and SHA-384 are truncated versions of SHA-256 and SHA-512 respectively, computed with different initial values. SHA-512/224 and SHA-512/256 are also truncated versions of SHA-512, but the initial values are generated using the method described in Federal Information Processing Standards (FIPS) PUB 180-4.
SHA-2 was first published by the National Institute of Standards and Technology (NIST) as a U.S. federal standard. The SHA-2 family of algorithms are patented in the U.S. The United States has released the patent under a royalty-free license.
As of 2024, the SHA-2 cryptographic hash function remains secure against known attacks, including those from quantum computers.

## Related

- [[SHA-1]]
- [[Message Authenticator Algorithm]]
- [[NIST hash function competition]]
- [[SHA-3]]
- [[Skein (hash function)]]
- [[SM3 (hash function)]]
- [[Abramowitz and Stegun]]
- [[Advanced Encryption Standard]]
- [[Argon2]]
- [[Ascon (cipher)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SHA-2