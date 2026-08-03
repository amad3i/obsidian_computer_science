---
title: "VEST"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/VEST"
wikipedia_categories: ["Cryptographic hash functions", "Message authentication codes", "Stream ciphers"]
related: ["[[Gimli (cipher)]]", "[[Panama (cryptography)]]", "[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]"]
---

# VEST

VEST (Very Efficient Substitution Transposition) ciphers are a set of families of general-purpose hardware-dedicated ciphers that support single pass authenticated encryption and can operate as collision-resistant hash functions designed by Sean O'Neil, Benjamin Gittins and Howard Landman. VEST cannot be implemented efficiently in software.
VEST is based on a balanced T-function that can also be described as a bijective nonlinear feedback shift register with parallel feedback (NLPFSR) or as a substitution–permutation network, which is assisted by a non-linear RNS-based counter. The four VEST family trees described in the cipher specification are VEST-4, VEST-8, VEST-16, and VEST-32. VEST ciphers support keys and IVs of variable sizes and instant re-keying. All VEST ciphers release output on every clock cycle.
All the VEST variants are covered by European Patent Number EP 1820295(B1), owned by Synaptic Laboratories.
VEST was a Phase 2 Candidate in the eSTREAM competition in the hardware portfolio, but was not a Phase 3 or Focus candidate and so is not part of the final portfolio.

## Related

- [[Gimli (cipher)]]
- [[Panama (cryptography)]]
- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/VEST