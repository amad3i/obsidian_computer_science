---
title: "Fast syndrome-based hash"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_syndrome-based_hash"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[FORK-256]]", "[[Gimli (cipher)]]"]
---

# Fast syndrome-based hash

In cryptography, the fast syndrome-based hash functions (FSB) are a family of cryptographic hash functions introduced in 2003 by Daniel Augot, Matthieu Finiasz, and Nicolas Sendrier.
Unlike most other cryptographic hash functions in use today, FSB can to a certain extent be proven to be secure. More exactly, it can be proven that breaking FSB is at least as difficult as solving a certain NP-complete problem known as regular syndrome decoding so FSB is provably secure. Though it is not known whether NP-complete problems are solvable in polynomial time, it is often assumed that they are not.
Several versions of FSB have been proposed, the latest of which was submitted to the SHA-3 cryptography competition but was rejected in the first round. Though all versions of FSB claim provable security, some preliminary versions were eventually broken. 
The design of the latest version of FSB has however taken this attack into account and remains secure to all currently known attacks.
As usual, provable security comes at a cost. FSB is slower than traditional hash functions and uses quite a lot of memory, which makes it impractical on memory constrained environments. Furthermore, the compression function used in FSB needs a large output size to guarantee security. This last problem has been solved in recent versions by simply compressing the output by another compression function called Whirlpool. However, though the authors argue that adding this last compression does not reduce security, it makes a formal security proof impossible.

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]
- [[FORK-256]]
- [[Gimli (cipher)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast_syndrome-based_hash