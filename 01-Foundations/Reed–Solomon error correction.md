---
title: "Reed–Solomon error correction"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Reed–Solomon_error_correction"
wikipedia_categories: ["Coding theory", "Error detection and correction"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]"]
---

# Reed–Solomon error correction

In information theory and coding theory, Reed–Solomon codes are a group of error-correcting codes that were introduced by Irving S. Reed and Gustave Solomon in 1960.
They have many applications, including consumer technologies such as MiniDiscs, CDs, DVDs, Blu-ray discs, QR codes, Data Matrix, data transmission technologies such as DSL and WiMAX, broadcast systems such as satellite communications, DVB and ATSC, and storage systems such as RAID 6.
Reed–Solomon codes operate on a block of data treated as a set of finite-field elements called symbols. Reed–Solomon codes RS(n, k) are able to detect and correct multiple symbol errors. By adding t = n − k check symbols to the data, a Reed–Solomon code can detect (but not correct) any combination of up to t erroneous symbols, or locate and correct up to ⌊t/2⌋ erroneous symbols at unknown locations. As an erasure code, it can correct up to t erasures at locations that are known and provided to the algorithm, or it can detect and correct combinations of errors and erasures. Reed–Solomon codes are also suitable as multiple-burst bit-error correcting codes, since a sequence of b + 1 consecutive bit errors can affect at most two symbols of size b. The choice of t is up to the designer of the code and may be selected within wide limits.
There are two different Reed-Solomon encoding schemes, called original view and BCH view in this article. The history section explains the origins of this.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Coset leader]]
- [[Delsarte–Goethals code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reed–Solomon_error_correction