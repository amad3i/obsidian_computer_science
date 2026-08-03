---
title: "Signatures with efficient protocols"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Signatures_with_efficient_protocols"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Signatures with efficient protocols

Signatures with efficient protocols are a form of digital signature invented by Jan Camenisch and Anna Lysyanskaya in 2001. In addition to being secure digital signatures, they need to allow for the efficient implementation of two protocols:

A protocol for computing a digital signature in a secure two-party computation protocol.
A protocol for proving knowledge of a digital signature in a zero-knowledge protocol.
In applications, the first protocol allows a signer to possess the signing key to issue a signature to a user (the signature owner) without learning all the messages being signed or the complete signature.
The second protocol allows the signature owner to prove that he has a signature on many messages without revealing the signature and only a (possibly) empty subset of the messages.
The combination of these two protocols allows for the implementation of digital credential and ecash protocols.

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

- Wikipedia: https://en.wikipedia.org/wiki/Signatures_with_efficient_protocols