---
title: "Time-lock puzzle"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Time-lock_puzzle"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Time-lock puzzle

A time-lock puzzle, or time-released cryptography, encrypts a message that cannot be decrypted until a specified amount of time has passed. The concept was first described by Timothy C. May, and a solution first introduced by Ron Rivest, Adi Shamir, and David A. Wagner in 1996. Time-lock puzzle are useful in cases where confidentiality of information is determined by time, such as a diarist who does not want their views released until 50 years after their death, an auction where bids are sealed until the bidding period is closed, electronic voting, and contract signing. They can additionally be used in creating further cryptographic primitives, such as verifiable delay functions and zero knowledge proofs.
Time-released cryptography can be achieved through several different mechanisms.

Use mathematical problems requiring sequential calculations to solve, and cannot be solved with parallelization. Thus, adding more computers to a problem will not help solve the problem faster.
Use of a trusted agent, or multiple agents who each hold a part of the message and cryptographic keys, who release the message after a specified time period has passed.
Distribute public encryption keys to users, and place private cryptographic keys with a trusted agent in an offline location, to be released at a later date.

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

- Wikipedia: https://en.wikipedia.org/wiki/Time-lock_puzzle