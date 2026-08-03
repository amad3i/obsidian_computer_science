---
title: "Pepper (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Pepper_(cryptography)"
wikipedia_categories: ["Cryptography", "Password authentication"]
related: ["[[Passphrase]]", "[[Password strength]]", "[[Password-authenticated key agreement]]", "[[Salt (cryptography)]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]"]
---

# Pepper (cryptography)

In cryptography, a pepper is a secret added to an input such as a password during hashing with a cryptographic hash function. This value differs from a salt in that it is not stored alongside a password hash, but rather the pepper is kept separate using another mechanism, such as a Hardware Security Module.  Note that the National Institute of Standards and Technology refers to this value as a secret key rather than a pepper. A pepper is similar in concept to a salt or an encryption key. It is like a salt in that it is a randomized value that is added to a password hash, and it is similar to an encryption key in that it should be kept secret.
A pepper performs a comparable role to a salt or an encryption key, but while a salt is not secret (merely unique) and can be stored alongside the hashed output, a pepper is secret and must not be stored with the output. The hash and salt are usually stored in a database, but, if stored, a pepper must be stored separately to prevent it from being obtained by the attacker in case of a database breach.

## Related

- [[Passphrase]]
- [[Password strength]]
- [[Password-authenticated key agreement]]
- [[Salt (cryptography)]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pepper_(cryptography)