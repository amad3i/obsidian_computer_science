---
title: "Link encryption"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Link_encryption"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Link encryption

Link encryption is an approach to communications security that encrypts and decrypts all network traffic at each network routing point (e.g. network switch, or node through which it passes) until arrival at its final destination. This repeated decryption and encryption is necessary to allow the routing information contained in each transmission to be read and employed further to direct the transmission toward its destination, before which it is re-encrypted. This contrasts with end-to-end encryption where internal information, but not the header/routing information, is encrypted by the sender at the point of origin and only decrypted by the intended recipient.
Link encryption offers two main advantages:

encryption is automatic so there is less opportunity for human error.
if the communications link operates continuously and carries an unvarying level of traffic, link encryption defeats traffic analysis.
On the other hand, end-to-end encryption ensures only the intended recipient has access to the plaintext. Link encryption can be used with end-to-end systems by superencrypting the messages. Bulk encryption refers to encrypting a large number of circuits at once, after they have been multiplexed.

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

- Wikipedia: https://en.wikipedia.org/wiki/Link_encryption