---
title: "Security level"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Security_level"
wikipedia_categories: ["Computational hardness assumptions", "Cryptography"]
related: ["[[Discrete logarithm]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# Security level

In cryptography, security level is a measure of the strength that a cryptographic primitive — such as a cipher or hash function — achieves. Security level is usually expressed as a number of "bits of security" (also security strength), where n-bit security means that the attacker would have to perform 2n operations to break it, but other methods have been proposed that more closely model the costs for an attacker. This allows for convenient comparison between algorithms and is useful when combining multiple primitives in a hybrid cryptosystem, so there is no clear weakest link. For example, AES-128 (key size 128 bits) is designed to offer a 128-bit security level, which is considered roughly equivalent to a RSA using 3072-bit key.
In this context, security claim or target security level is the security level that a primitive was initially designed to achieve, although "security level" is also sometimes used in those contexts. When attacks are found that have lower cost than the security claim, the primitive is considered broken.

## Related

- [[Discrete logarithm]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Security_level