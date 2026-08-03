---
title: "Completeness (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Completeness_(cryptography)"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]", "[[Cover-coding]]"]
---

# Completeness (cryptography)

In cryptography, a boolean function is said to be complete if the value of each output bit depends on all input bits. 
This is a desirable property to have in an encryption cipher, so that if one bit of the input (plaintext) is changed, every bit of the output (ciphertext) has an average of 50% probability of changing. The easiest way to show why this is good is the following: consider that if we changed our 8-byte plaintext's last byte, it would only have any effect on the 8th byte of the ciphertext. This would mean that if the attacker guessed 256 different plaintext-ciphertext pairs, he would always know the last byte of every 8byte sequence we send (effectively 12.5% of all our data). Finding out 256 plaintext-ciphertext pairs is not hard at all in the internet world, given that standard protocols are used, and standard protocols have standard headers and commands (e.g. "get", "put", "mail from:", etc.) which the attacker can safely guess. On the other hand, if our cipher has this property (and is generally secure in other ways, too), the attacker would need to collect 264 (~1020) plaintext-ciphertext pairs to crack the cipher in this way.

## Related

- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]
- [[Cover-coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Completeness_(cryptography)