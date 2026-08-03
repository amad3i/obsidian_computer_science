---
title: "Tiger (hash function)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Tiger_(hash_function)"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# Tiger (hash function)

In cryptography, Tiger is a cryptographic hash function designed by Ross Anderson and Eli Biham in 1995 for efficiency on 64-bit platforms. The size of a Tiger hash value is 192 bits. Truncated versions (known as Tiger/128 and Tiger/160) can be used for compatibility with protocols assuming a particular hash size. Unlike the SHA-2 family, no distinguishing initialization values are defined; they are simply prefixes of the full Tiger/192 hash value.
Tiger2 is a variant where the message is padded by first appending a byte with the hexadecimal value of 0x80 as in MD4, MD5 and SHA, rather than with the hexadecimal value of 0x01 as in the case of Tiger. The two variants are otherwise identical.

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]
- [[Fast syndrome-based hash]]
- [[FORK-256]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tiger_(hash_function)