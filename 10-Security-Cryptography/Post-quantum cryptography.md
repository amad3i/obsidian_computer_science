---
title: "Post-quantum cryptography"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Post-quantum_cryptography"
wikipedia_categories: ["Cryptography", "Post-quantum cryptography"]
related: ["[[Quantum Threat]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# Post-quantum cryptography

Post-quantum cryptography (PQC), sometimes referred to as quantum-proof, quantum-safe, or quantum-resistant, is the development of cryptographic algorithms (usually public-key algorithms) that are currently thought, but not proven, to be secure against a cryptanalytic attack by a quantum computer. Most widely used public-key algorithms rely on the difficulty of one of three mathematical problems: the integer factorization problem, the discrete logarithm problem, or the elliptic-curve discrete logarithm problem. All of these problems could be easily solved on a sufficiently powerful quantum computer running Shor's algorithm or possibly alternatives.
As of 2026, quantum computers lack the processing power to break widely used cryptographic algorithms; however, because of the length of time required for migration to quantum-safe cryptography, cryptographers are already designing new algorithms to prepare for Y2Q or "Q-Day", the day when current algorithms will be vulnerable to quantum computing attacks. Mosca's theorem provides the risk analysis framework that helps organizations identify how quickly they need to start migrating.
Their work has gained attention from academics and industry through the PQCrypto conference series hosted since 2006, several workshops on Quantum Safe Cryptography hosted by the European Telecommunications Standards Institute (ETSI), and the Institute for Quantum Computing. The rumoured existence of widespread harvest now, decrypt later programs has also been seen as a motivation for the early introduction of post-quantum algorithms, as data recorded now may still remain sensitive many years into the future.
In contrast to the threat quantum computing poses to current public-key algorithms, most current symmetric cryptographic algorithms and hash functions are considered to be relatively secure against attacks by quantum computers. While the quantum Grover's algorithm does speed up attacks against symmetric ciphers, doubling the key size can effectively counteract these attacks. Thus post-quantum symmetric cryptography does not need to differ significantly from current symmetric cryptography.
In 2024, the U.S. National Institute of Standards and Technology (NIST) released final versions of its first three Post-Quantum Cryptography Standards.

## Related

- [[Quantum Threat]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Post-quantum_cryptography