---
title: "RadioGatún"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/RadioGatún"
wikipedia_categories: ["Block ciphers", "Cryptographic hash functions", "Extendable-output functions"]
related: ["[[Ascon (cipher)]]", "[[Panama (cryptography)]]", "[[SHA-3]]", "[[Skein (hash function)]]", "[[Advanced Encryption Standard]]", "[[Argon2]]", "[[Bcrypt]]", "[[Block cipher]]", "[[CDMF]]", "[[Collision attack]]"]
---

# RadioGatún

RadioGatún is a cryptographic hash primitive created by Guido Bertoni, Joan Daemen, Michaël Peeters, and Gilles Van Assche.  It was first publicly presented at the NIST Second Cryptographic Hash Workshop, held in Santa Barbara, California, on August 24–25, 2006, as part of the NIST hash function competition.  The same team that developed RadioGatún went on to make considerable revisions to this cryptographic primitive, leading to the Keccak SHA-3 algorithm.
RadioGatún is a family of 64 different hash functions, distinguished by a single parameter, the word width in bits (w), adjustable between 1 and 64.  The only word sizes with official test vectors are the 32-bit and 64-bit variants of RadioGatún.  The algorithm uses 58 words, each using w bits, to store its internal state, so the 32-bit version needs 232 bytes to store its state (since each word needs 32 bits or four bytes, and 58 multiplied by four is 232) and the 64-bit version 464 bytes (each word using eight bytes).
Although RadioGatún is a derivative of Panama, a stream cipher and hash construction from the late 1990s whose hash construction has been broken, RadioGatún does not have Panama's weaknesses when used as a hash function.  As of 2022, RadioGatún is still a secure hash function; the largest version of RadioGatún that is broken is the one with a word size of two bits.  RadioGatún has a claimed security strength of 304 bits for the 32-bit version and 608 bits for the 64-bit version.  The best known cryptanalysis has not broken this claim: It needs 352 bits of work for the 32-bit version and 704 bits of work for the 64-bit version.
RadioGatún can be used either as a hash function or a stream cipher; it can output an arbitrarily long stream of pseudo-random numbers; this kind of hash construction is now known as an "extendable-output function" (XOF).

## Related

- [[Ascon (cipher)]]
- [[Panama (cryptography)]]
- [[SHA-3]]
- [[Skein (hash function)]]
- [[Advanced Encryption Standard]]
- [[Argon2]]
- [[Bcrypt]]
- [[Block cipher]]
- [[CDMF]]
- [[Collision attack]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RadioGatún