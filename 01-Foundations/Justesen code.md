---
title: "Justesen code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Justesen_code"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Finite fields"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Concatenated error correction code]]", "[[Generalized minimum-distance decoding]]", "[[Homomorphic signatures for network coding]]", "[[Preparata code]]", "[[Srivastava code]]", "[[Zyablov bound]]", "[[Algebraic geometry code]]"]
---

# Justesen code

In coding theory, Justesen codes form a class of error-correcting codes that have a constant rate, constant relative distance, and a constant alphabet size.
Before the Justesen error correction code was discovered, no error correction code was known that had all of these three parameters as a constant.
Subsequently, other ECC codes with this property have been discovered, for example expander codes.
These codes have important applications in computer science such as in the construction of small-bias sample spaces.
Justesen codes are derived as the code concatenation of a Reed–Solomon code and the Wozencraft ensemble.
The Reed–Solomon codes used achieve constant rate and constant relative distance at the expense of an alphabet size that is linear in the message length.
The Wozencraft ensemble is a family of codes that achieve constant rate and constant alphabet size, but the relative distance is only constant for most of the codes in the family.
The concatenation of the two codes first encodes the message using the Reed–Solomon code, and then encodes each symbol of the codeword further using a code from the Wozencraft ensemble – using a different code of the ensemble at each position of the codeword.
This is different from usual code concatenation where the inner codes are the same for each position. The Justesen code can be constructed very efficiently using only logarithmic space.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Concatenated error correction code]]
- [[Generalized minimum-distance decoding]]
- [[Homomorphic signatures for network coding]]
- [[Preparata code]]
- [[Srivastava code]]
- [[Zyablov bound]]
- [[Algebraic geometry code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Justesen_code