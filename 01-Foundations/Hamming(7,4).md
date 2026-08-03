---
title: "Hamming(7,4)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hamming(7,4)"
wikipedia_categories: ["Coding theory", "Computer arithmetic", "Error detection and correction"]
related: ["[[Hamming code]]", "[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]"]
---

# Hamming(7,4)

In coding theory, Hamming(7,4) is a linear error-correcting code that encodes four bits of data into seven bits by adding three parity bits. It is a member of a larger family of  Hamming codes, but the term Hamming code often refers to this specific code that Richard W. Hamming introduced in 1950. At the time, Hamming worked at Bell Telephone Laboratories and was frustrated with the error-prone punched card reader, which is why he started working on error-correcting codes.
The Hamming code adds three additional check bits to every four data bits of the message. Hamming's (7,4) algorithm can correct any single-bit error, or detect all single-bit and two-bit errors. In other words, the minimal Hamming distance between any two correct codewords is 3, and received words can be correctly decoded if they are at a distance of at most one from the codeword that was transmitted by the sender. This means that for transmission medium situations where burst errors do not occur, Hamming's (7,4) code is effective (as the medium would have to be extremely noisy for two out of seven bits to be flipped).
In quantum information, the Hamming (7,4) is used as the base for the Steane code, a type of CSS code used for quantum error correction.

## Related

- [[Hamming code]]
- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Coset leader]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hamming(7,4)