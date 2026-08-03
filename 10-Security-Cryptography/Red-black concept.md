---
title: "Red/black concept"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Red/black_concept"
wikipedia_categories: ["Cryptography", "Cryptography stubs", "Secure communication", "Security engineering"]
related: ["[[Blacker (security)]]", "[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]"]
---

# Red/black concept

The red/black concept, named in comparison to a typewriter ribbon and sometimes called the red–black architecture
or red/black engineering,
refers to the careful segregation in cryptographic systems of signals that contain sensitive or classified plaintext information (red signals) from those that carry encrypted information, or ciphertext (black signals). Therefore, the red side is usually considered the internal side, and the black side the more public side, with often some sort of guard, firewall or data-diode between the two.
In NSA jargon, encryption devices are often called blackers, because they convert red signals to black. TEMPEST standards spelled out in Tempest/2-95 specify shielding or a minimum physical distance between wires or equipment carrying or processing red and black signals.
Different organizations have differing requirements for the separation of red and black fiber-optic cables.
Red/black terminology is also applied to cryptographic keys. Black keys have themselves been encrypted with  a "key encryption key" (KEK) and are therefore benign.  Red keys are not encrypted and must be treated as highly sensitive material.

## Related

- [[Blacker (security)]]
- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Red/black_concept