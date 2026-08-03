---
title: "Quark (hash function)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Quark_(hash_function)"
wikipedia_categories: ["Cryptographic hash functions", "Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Argon2]]", "[[Array controller based encryption]]", "[[Ascon (cipher)]]"]
---

# Quark (hash function)

Quark is a cryptographic hash function (family).
It was designed by Jean-Philippe Aumasson, Luca Henzen, Willi Meier and María Naya-Plasencia.
Quark was created because of the expressed need by application designers (notably for implementing RFID protocols) for a lightweight cryptographic hash function.
The SHA-3 NIST hash function competition concerned general-purpose designs and focused on software performance.
Quark is a lightweight hash function, based on a single security level and on the sponge construction, to minimize memory requirements. Inspired by the lightweight ciphers Grain and KATAN, the hash function family Quark is composed of the three instances u-Quark, d-Quark, and t-Quark. Hardware benchmarks show that Quark compares well to previous lightweight hashes.
For example, the u-Quark instance conjecturally provides at least 64-bit security against all attacks (collisions, multicollisions, distinguishers, etc.), fits in 1379 gate-equivalents, and consumes in average 2.44 μW at 100 kHz in 0.18 μm ASIC.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Argon2]]
- [[Array controller based encryption]]
- [[Ascon (cipher)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quark_(hash_function)