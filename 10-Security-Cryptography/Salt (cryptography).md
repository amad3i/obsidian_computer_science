---
title: "Salt (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Salt_(cryptography)"
wikipedia_categories: ["Cryptography", "Password authentication"]
related: ["[[Passphrase]]", "[[Password strength]]", "[[Password-authenticated key agreement]]", "[[Pepper (cryptography)]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]"]
---

# Salt (cryptography)

In cryptography, a salt is random data fed as an additional input to a one-way function that hashes data, a password or passphrase. Salting helps defend against attacks that use precomputed tables (e.g. rainbow tables), by vastly growing the size of table needed for a successful attack. It also helps protect passwords that occur multiple times in a database, as a new salt is used for each password instance. Additionally, salting does not place any burden on users. 
Typically, a unique salt is randomly generated for each password. The salt and the password (or its version after key stretching) are concatenated and fed to a cryptographic hash function, and the output hash value is then stored with the salt in a database. The salt does not need to be encrypted, because knowing the salt would not help the attacker.
Salting is broadly used in cybersecurity, from Unix system credentials to Internet security.
Salts are related to cryptographic nonces.

## Related

- [[Passphrase]]
- [[Password strength]]
- [[Password-authenticated key agreement]]
- [[Pepper (cryptography)]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Salt_(cryptography)