---
title: "Master/Session"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Master/Session"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Master/Session

In cryptography, Master/Session is a key management scheme in which a pre-shared Key Encrypting Key (called the "Master" key) is used to encrypt a randomly generated and insecurely communicated Working Key (called the "Session" key). The Working Key is then used for encrypting the data to be exchanged. Its advantage is simplicity, but it suffers the disadvantage of having to communicate the pre-shared Key Exchange Key, which can be difficult to update in the event of compromise.
The Master/Session technique was created in the days before asymmetric techniques, such as Diffie-Hellman, were invented. This technique still finds widespread use in the financial industry, and is routinely used between corporate parties such as issuers, acquirers, switches. Its use in device communications (such as PIN pads), however, is in decline given the advantages of techniques such as DUKPT.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]
- [[Batch cryptography]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Master/Session