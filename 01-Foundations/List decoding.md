---
title: "List decoding"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/List_decoding"
wikipedia_categories: ["Coding theory", "Computational complexity theory", "Error detection and correction"]
related: ["[[Folded Reed–Solomon code]]", "[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Computationally bounded adversary]]", "[[Concatenated error correction code]]"]
---

# List decoding

In coding theory, list decoding is an alternative to unique decoding of error-correcting codes for large error rates. The notion was proposed by Elias in the 1950s. The main idea behind list decoding is that the decoding algorithm instead of outputting a single possible message outputs a list of possibilities one of which is correct. This allows for handling a greater number of errors than that allowed by unique decoding.
The unique decoding model in coding theory, which is constrained to output a single valid codeword from the received word could not tolerate a greater fraction of errors.  This resulted in a gap between the error-correction performance for stochastic noise models (proposed by Shannon) and the adversarial noise model (considered by Richard Hamming). Since the mid 90s, significant algorithmic progress by the coding theory community has bridged this gap. Much of this progress is based on a relaxed error-correction model called list decoding, wherein the decoder outputs a list of codewords for worst-case pathological error patterns where the actual transmitted codeword is included in the output list. In case of typical error patterns though, the decoder outputs a unique single codeword, given a received word, which is almost always the case (However, this is not known to be true for all codes). The improvement here is significant in that the error-correction performance doubles. This is because now the decoder is not confined by the half-the-minimum distance barrier. This model is very appealing because having a list of codewords is certainly better than just giving up. The notion of list-decoding has many interesting applications in complexity theory.
The way the channel noise is modeled plays a crucial role in that it governs the rate at which reliable communication is possible. There are two main schools of thought in modeling the channel behavior:

Probabilistic noise model studied by Shannon in which the channel noise is modeled precisely in the sense that the probabilistic behavior of the channel is well known and the probability of occurrence of too many or too few errors is low
Worst-case or adversarial noise model considered by Hamming in which the channel acts as an adversary that arbitrarily corrupts the codeword subject to a bound on the total number of errors.
The highlight of list-decoding is that even under adversarial noise conditions, it is possible to achieve the information-theoretic optimal trade-off between rate and fraction of errors that can be corrected. Hence, in a sense this is like improving the error-correction performance to that possible in case of a weaker, stochastic noise model.

## Related

- [[Folded Reed–Solomon code]]
- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Computationally bounded adversary]]
- [[Concatenated error correction code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/List_decoding