---
title: "MOSQUITO"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/MOSQUITO"
wikipedia_categories: ["Cryptographic algorithms", "Cryptography stubs"]
related: ["[[CDMF]]", "[[PEGASUS]]", "[[Rip van Winkle cipher]]", "[[Alternant code]]", "[[Ascon (cipher)]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[Batch cryptography]]", "[[BB84]]", "[[Beaufort cipher]]"]
---

# MOSQUITO

In cryptography, MOSQUITO was a stream cipher algorithm designed by Joan Daemen and Paris Kitsos. They submitted it to the eSTREAM project, which was a part of eCRYPT. While presenting it in a document published in 2005, they explained some of their design intentions: Self-synchronizing stream encryption can be performed by using a block cipher in CFB mode. However, for single-bit self-synchronizing stream encryption, this is very inefficient. Therefore we believe that it would be useful to design a dedicated self-synchronizing stream cipher that is efficient in hardware.
It was subsequently broken by Antoine Joux and Frédéric Muller in 2006, who had this to say in their conference paper: All the dedicated Self-Synchronizing Stream Ciphers (SSSC) of the KNOT-MOSQUITO family are subject to differential chosen ciphertext attacks. Our results, combined with previous results on HBB, KNOT and SSS show that it is extremely difficult to design a SSSC resistant against chosen-ciphertext attacks.A tweaked version named MOUSTIQUE was proposed which made it to Phase 3 of the eSTREAM evaluation process as the only self-synchronizing cipher remaining, where it was noted that "in reaching the third phase of eSTREAM all the algorithms in this book have made a significant advance in the development of stream ciphers.
However, MOUSTIQUE was subsequently broken by Käsper et al., leaving the design of a secure and efficient self-synchronizing stream cipher as an open research problem.

## Related

- [[CDMF]]
- [[PEGASUS]]
- [[Rip van Winkle cipher]]
- [[Alternant code]]
- [[Ascon (cipher)]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[Batch cryptography]]
- [[BB84]]
- [[Beaufort cipher]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MOSQUITO