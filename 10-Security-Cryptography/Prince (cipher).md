---
title: "Prince (cipher)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Prince_(cipher)"
wikipedia_categories: ["Block ciphers", "Cryptography"]
related: ["[[Advanced Encryption Standard]]", "[[Format-preserving encryption]]", "[[PRESENT]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]"]
---

# Prince (cipher)

Prince is a block cipher targeting low latency, unrolled hardware implementations. It is based on the so-called FX construction. Its most notable feature is the alpha reflection: the decryption is the encryption with a related key which is very cheap to compute. Unlike most other "lightweight" ciphers, it has a small number of rounds and the layers constituting a round have low logic depth. As a result, fully unrolled implementation are able to reach much higher frequencies than AES or PRESENT. According to the authors, for the same time constraints and technologies, PRINCE uses 6–7 times less area than PRESENT-80 and 14–15 times less area than AES-128.

## Related

- [[Advanced Encryption Standard]]
- [[Format-preserving encryption]]
- [[PRESENT]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Prince_(cipher)