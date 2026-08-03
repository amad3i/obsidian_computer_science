---
title: "Generalized minimum-distance decoding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalized_minimum-distance_decoding"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Finite fields", "Information theory"]
related: ["[[Homomorphic signatures for network coding]]", "[[Zyablov bound]]", "[[Alternant code]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Concatenated error correction code]]", "[[Justesen code]]", "[[Linear network coding]]", "[[Preparata code]]", "[[Srivastava code]]"]
---

# Generalized minimum-distance decoding

In coding theory, generalized minimum-distance (GMD) decoding provides an efficient algorithm for decoding concatenated codes, which is based on using an errors-and-erasures decoder for the outer code.
A naive decoding algorithm for concatenated codes can not be an optimal way of decoding because it does not take into account the information that maximum likelihood decoding (MLD) gives. In other words, in the naive algorithm, inner received codewords are treated the same regardless of the difference between their hamming distances. Intuitively, the outer decoder should place higher confidence in symbols whose inner encodings are close to the received word. David Forney in 1966 devised a better algorithm called generalized minimum distance (GMD) decoding which makes use of those information better. This method is achieved by measuring confidence of each received codeword, and erasing symbols whose confidence is below a desired value. And GMD decoding algorithm was one of the first examples of soft-decision decoders. We will present three versions of the GMD decoding algorithm. The first two will be randomized algorithms while the last one will be a deterministic algorithm.

## Related

- [[Homomorphic signatures for network coding]]
- [[Zyablov bound]]
- [[Alternant code]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Concatenated error correction code]]
- [[Justesen code]]
- [[Linear network coding]]
- [[Preparata code]]
- [[Srivastava code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generalized_minimum-distance_decoding