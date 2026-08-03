---
title: "Crypt (C)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Crypt_(C)"
wikipedia_categories: ["Broken cryptographic algorithms", "Computer access control protocols", "Cryptographic hash functions", "Key derivation functions", "Password authentication"]
related: ["[[Argon2]]", "[[Bcrypt]]", "[[MS-CHAP]]", "[[RADIUS]]", "[[Scrypt]]", "[[Yescrypt]]", "[[Ascon (cipher)]]", "[[Challenge-Handshake Authentication Protocol]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]"]
---

# Crypt (C)

crypt is a POSIX C library function. It is typically used to compute the hash of user account passwords. The function outputs a text string which also encodes the salt (usually the first two characters are the salt itself and the rest is the hashed result), and identifies the hash algorithm used (defaulting to the "traditional" one explained below). This output string forms a password record, which is usually stored in a text file.
More formally, crypt provides cryptographic key derivation functions for password validation and storage on Unix systems.

## Related

- [[Argon2]]
- [[Bcrypt]]
- [[MS-CHAP]]
- [[RADIUS]]
- [[Scrypt]]
- [[Yescrypt]]
- [[Ascon (cipher)]]
- [[Challenge-Handshake Authentication Protocol]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Crypt_(C)