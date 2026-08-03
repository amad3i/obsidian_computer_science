---
title: "Strong secrecy"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Strong_secrecy"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Strong secrecy

Strong secrecy is a term used in formal proof-based cryptography for making propositions about the security of cryptographic protocols. It is a stronger notion of security than syntactic (or weak) secrecy. Strong secrecy is related with the concept of semantic security or indistinguishability used in the computational proof-based approach. Bruno Blanchet provides the following definition for strong secrecy:

Strong secrecy means that an adversary cannot see any difference when the value of the secret changes
For example, if a process encrypts a message m an attacker can differentiate between different messages, since their ciphertexts will be different. Thus m is not a strong secret. If however, probabilistic encryption were used, m would be a strong secret. The randomness incorporated into the encryption algorithm will yield different ciphertexts for the same value of m.

## Related

- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Strong_secrecy