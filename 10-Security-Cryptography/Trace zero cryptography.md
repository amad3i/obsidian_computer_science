---
title: "Trace zero cryptography"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Trace_zero_cryptography"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Trace zero cryptography

First proposed by Gerhard Frey in 1998, trace zero cryptography refers to the use of trace zero varieties (TZV) for cryptographic purpose. Trace zero varieties are subgroups of the divisor class group on a low genus hyperelliptic curve defined over a finite field. These groups can be used to establish asymmetric cryptography using the discrete logarithm problem as cryptographic primitive.
Trace zero varieties feature a better scalar multiplication performance than elliptic curves. This allows fast arithmetic in these groups, which can speed up the calculations with a factor 3 compared with elliptic curves and hence speed up the cryptosystem.
Another advantage is that for groups of cryptographically relevant size, the order of the group can simply be calculated using the characteristic polynomial of the Frobenius endomorphism. This is not the case, for example, in elliptic curve cryptography when the group of points of an elliptic curve over a prime field is used for cryptographic purpose.
However, to represent an element of the trace zero variety more bits are needed compared with elements of elliptic or hyperelliptic curves. Another disadvantage is the fact that it is possible to reduce the security of the TZV of 1/6th of the bit length using cover attack.

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

- Wikipedia: https://en.wikipedia.org/wiki/Trace_zero_cryptography