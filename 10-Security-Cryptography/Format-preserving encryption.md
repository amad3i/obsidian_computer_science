---
title: "Format-preserving encryption"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Format-preserving_encryption"
wikipedia_categories: ["Block ciphers", "Cryptography"]
related: ["[[Advanced Encryption Standard]]", "[[PRESENT]]", "[[Prince (cipher)]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]"]
---

# Format-preserving encryption

In cryptography, format-preserving encryption (FPE),  refers to encrypting in such a way that the output (the ciphertext) is in the same format as the input (the plaintext). The meaning of "format" varies. Typically only finite sets of characters are used; numeric, alphabetic or alphanumeric. For example:

Encrypting a 16-digit credit card number so that the ciphertext is another 16-digit number.
Encrypting an English word so that the ciphertext is another English word.
Encrypting an n-bit number so that the ciphertext is another n-bit number (this is the definition of an n-bit block cipher).
For such finite domains, and for the purposes of the discussion below, the cipher is equivalent to a permutation of N integers {0, ... , N−1} where N is the size of the domain.

## Related

- [[Advanced Encryption Standard]]
- [[PRESENT]]
- [[Prince (cipher)]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Format-preserving_encryption