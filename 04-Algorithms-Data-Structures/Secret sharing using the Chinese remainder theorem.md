---
title: "Secret sharing using the Chinese remainder theorem"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Secret_sharing_using_the_Chinese_remainder_theorem"
wikipedia_categories: ["Cryptographic algorithms"]
related: ["[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[CryptGenRandom]]", "[[Crypto++]]"]
---

# Secret sharing using the Chinese remainder theorem

Secret sharing consists of recovering a secret S from a set of shares, each containing partial information about the secret. The Chinese remainder theorem (CRT) states that for a given system of simultaneous congruence equations, the solution is unique in some Z/nZ, with n > 0 under some appropriate conditions on the congruences. Secret sharing can thus use the CRT to produce the shares presented in the congruence equations and the secret could be recovered by solving the system of congruences to get the unique solution, which will be the secret to recover.

## Related

- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[CryptGenRandom]]
- [[Crypto++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Secret_sharing_using_the_Chinese_remainder_theorem