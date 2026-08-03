---
title: "Hyper-encryption"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hyper-encryption"
wikipedia_categories: ["Cryptography", "Cryptography stubs", "Information theory"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Hyper-encryption

Hyper-encryption is a form of encryption invented by Michael O. Rabin which uses a high-bandwidth source of public random bits, together with a secret key that is shared by only the sender and recipient(s) of the message. It uses the assumptions of Ueli Maurer's bounded-storage model as the basis of its secrecy. Although everyone can see the data, decryption by adversaries without the secret key is still not feasible, because of the space limitations of storing enough data to mount an attack against the system.
Unlike almost all other cryptosystems except the one-time pad, hyper-encryption can be proved to be information-theoretically secure, provided the storage bound cannot be surpassed. Moreover, if the necessary public information cannot be stored at the time of transmission, the plaintext can be shown to be impossible to recover, regardless of the computational capacity available to an adversary in the future, even if they have access to the secret key at that future time.
A highly energy-efficient implementation of a hyper-encryption chip was demonstrated by Krishna Palem et al. using the Probabilistic CMOS or PCMOS technology and was shown to be  ~205 times more efficient in terms of Energy-Performance-Product.

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

- Wikipedia: https://en.wikipedia.org/wiki/Hyper-encryption