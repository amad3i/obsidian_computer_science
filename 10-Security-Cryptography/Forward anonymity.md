---
title: "Forward anonymity"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Forward_anonymity"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Forward anonymity

Forward anonymity is a property of a cryptographic system which prevents an attacker who has recorded past encrypted communications from discovering its contents and participants in the future. This property is analogous to forward secrecy.
An example of a system which uses forward anonymity is a public key cryptography system, where the public key is well-known and used to encrypt a message, and an unknown private key is used to decrypt it. In this system, one of the keys is always said to be compromised, but messages and their participants are still unknown by anyone without the corresponding private key.
In contrast, an example of a system which satisfies the perfect forward secrecy property is one in which a compromise of one key by an attacker (and consequent decryption of messages encrypted with that key) does not undermine the security of previously used keys. Forward secrecy does not refer to protecting the content of the message, but rather to the protection of keys used to decrypt messages.

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

- Wikipedia: https://en.wikipedia.org/wiki/Forward_anonymity