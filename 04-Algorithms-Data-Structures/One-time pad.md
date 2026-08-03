---
title: "One-time pad"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/One-time_pad"
wikipedia_categories: ["1882 introductions", "Cryptography", "Information-theoretically secure algorithms", "Stream ciphers"]
related: ["[[SFINKS]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# One-time pad

The one-time pad (OTP) is an encryption technique that cannot be cracked in cryptography. It requires the use of a single-use pre-shared key that is larger than or equal to the size of the message being sent. In this technique, a plaintext is paired with a random secret key (also referred to as a one-time pad). Then, each bit or character of the plaintext is encrypted by combining it with the corresponding bit or character from the pad using modular addition.
The resulting ciphertext is impossible to decrypt or break if the following four conditions are met:

The key must be at least as long as the plaintext.
The key must be truly random.
The key must never be reused in whole or in part.
The key must be kept completely secret by the communicating parties.
These requirements make the OTP the only known encryption system that is mathematically proven to be unbreakable under the principles of information theory.
Digital versions of one-time pad ciphers have been used by nations for critical diplomatic and military communication, but the problems of secure key distribution make them impractical for many applications.
First described by Frank Miller in 1882, the one-time pad was re-invented in 1917. On July 22, 1919, U.S. Patent 1,310,719 was issued to Gilbert Vernam for the XOR operation used for the encryption of a one-time pad. One-time use came later, when Joseph Mauborgne recognized that if the key tape were totally random, then cryptanalysis would be impossible.
To increase security, one-time pads were sometimes printed onto sheets of highly flammable nitrocellulose, so that they could easily be burned after use.

## Related

- [[SFINKS]]
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

- Wikipedia: https://en.wikipedia.org/wiki/One-time_pad