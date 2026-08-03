---
title: "White-box cryptography"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/White-box_cryptography"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# White-box cryptography

In cryptography, the white-box model refers to an extreme attack scenario, in which an adversary has full unrestricted access to a cryptographic implementation, most commonly of a block cipher such as the Advanced Encryption Standard (AES). A variety of security goals may be posed (see the section below), the most fundamental being "unbreakability", requiring that any (bounded) attacker should not be able to extract the secret key hardcoded in the implementation, while at the same time the implementation must be fully functional. In contrast, the black-box model only provides an oracle access to the analyzed cryptographic primitive (in the form of encryption and/or decryption queries). There is also a model in-between, the so-called gray-box model, which corresponds to additional information leakage from the implementation, more commonly referred to as side-channel leakage.
White-box cryptography is a practice and study of techniques for designing and attacking white-box implementations. It has many applications, including digital rights management (DRM), pay television, protection of cryptographic keys in the presence of malware, mobile payments and cryptocurrency wallets. Examples of DRM systems employing white-box implementations include CSS and Widevine.
White-box cryptography is closely related to the more general notions of obfuscation, in particular, to Black-box obfuscation, proven to be impossible, and to Indistinguishability obfuscation, constructed recently under well-founded assumptions but so far being infeasible to implement in practice.
As of January 2023, there are no publicly known unbroken white-box designs of standard symmetric encryption schemes. On the other hand, there exist many unbroken white-box implementations of dedicated block ciphers designed specifically to achieve incompressibility (see § Security goals).

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

- Wikipedia: https://en.wikipedia.org/wiki/White-box_cryptography