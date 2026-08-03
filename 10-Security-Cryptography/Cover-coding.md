---
title: "Cover-coding"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Cover-coding"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Cover-coding

Cover-coding is a technique for obscuring the data that is transmitted over an insecure link, to reduce the risks of snooping.  An example of cover-coding would be for the sender to perform a bitwise XOR (exclusive OR) of the original data with a password or random number which is known to both sender and receiver.  The resulting cover-coded data is then transmitted from sender to the receiver, who uncovers the original data by performing a further bitwise XOR (exclusive OR) operation on the received data using the same password or random number.
ISO 18000-6C (EPC Class 1 Generation 2) RFID tags protect some operations with a cover code.
The reader requests a random number from the tag,
and the tag responds with a new random number.
The reader then encrypts future communications with this number, using bitwise XOR, to the data it sends.
Cover coding is secure if the tag signal can't be intercepted and the random number is not re-used.
Compared to the loud transmissions from the reader,
tag backscatter is much weaker and difficult -- but not impossible -- to intercept.

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

- Wikipedia: https://en.wikipedia.org/wiki/Cover-coding