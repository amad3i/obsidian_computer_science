---
title: "Chaffing and winnowing"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Chaffing_and_winnowing"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Chaffing and winnowing

Chaffing and winnowing is a cryptographic technique to achieve confidentiality without using encryption when sending data over an insecure channel. The name is derived from agriculture: after grain has been harvested and threshed, it remains mixed together with inedible fibrous chaff.  The chaff and grain are then separated by winnowing, and the chaff is discarded. The cryptographic technique was conceived by Ron Rivest and published in an on-line article on 18 March 1998. Although it bears similarities to both traditional encryption and steganography, it cannot be classified under either category.
This technique allows the sender to deny responsibility for encrypting their message. When using chaffing and winnowing, the sender transmits the message unencrypted, in clear text. Although the sender and the receiver share a secret key, they use it only for authentication. However, a third party can make their communication confidential by simultaneously sending specially crafted messages through the same channel.

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

- Wikipedia: https://en.wikipedia.org/wiki/Chaffing_and_winnowing