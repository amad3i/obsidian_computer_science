---
title: "HKDF"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/HKDF"
wikipedia_categories: ["Cryptography", "Key derivation functions"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Argon2]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# HKDF

HKDF is a multi-purpose key derivation function (KDF) based on the HMAC message authentication code. HKDF follows "extract-then-expand" paradigm, where the KDF logically consists of two modules: the first stage takes the input keying material and "extracts" from it a fixed-length pseudorandom key, and then the second stage "expands" this key into several additional, independent pseudorandom keys as the output of the KDF.

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
- [[Backdoor (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HKDF