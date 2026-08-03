---
title: "SHA-3"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/SHA-3"
wikipedia_categories: ["Cryptographic hash functions", "Extendable-output functions", "NIST hash function competition", "Public-domain software with source code"]
related: ["[[Skein (hash function)]]", "[[Ascon (cipher)]]", "[[Grøstl]]", "[[JH (hash function)]]", "[[MD6]]", "[[NIST hash function competition]]", "[[Panama (cryptography)]]", "[[RadioGatún]]", "[[SANDstorm hash]]", "[[SHA-1]]"]
---

# SHA-3

SHA-3 (Secure Hash Algorithm 3) is the latest member of the Secure Hash Algorithm family of standards, released by NIST on August 5, 2015. Although part of the same series of standards, SHA-3 is internally different from the MD5-like structure of SHA-1 and SHA-2.
SHA-3 is a subset of the broader cryptographic primitive family Keccak ( or ), designed by Guido Bertoni, Joan Daemen, Michaël Peeters, and Gilles Van Assche, building upon RadioGatún. Keccak's authors have proposed additional uses for the function, not (yet) standardized by NIST, including a stream cipher, an authenticated encryption system, a "tree" hashing scheme for faster hashing on certain architectures, and AEAD ciphers Keyak and Ketje.
Keccak is based on a novel approach called sponge construction. The sponge construction is based on a pseudorandom permutation, and allows inputting ("absorbing" in sponge terminology) any amount of data, and outputting ("squeezing") any amount of data, while acting as a pseudorandom function with regard to all previous inputs. This leads to great flexibility.
As of 2022, NIST does not plan to withdraw SHA-2 or remove it from the revised Secure Hash Standard. The purpose of SHA-3 is that it can be directly substituted for SHA-2 in current applications if necessary, and to significantly improve the robustness of NIST's overall hash algorithm toolkit.
For small message sizes, the creators of the Keccak algorithms and the SHA-3 functions suggest using the faster function KangarooTwelve with adjusted parameters and a new tree hashing mode without extra overhead.

## Related

- [[Skein (hash function)]]
- [[Ascon (cipher)]]
- [[Grøstl]]
- [[JH (hash function)]]
- [[MD6]]
- [[NIST hash function competition]]
- [[Panama (cryptography)]]
- [[RadioGatún]]
- [[SANDstorm hash]]
- [[SHA-1]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SHA-3