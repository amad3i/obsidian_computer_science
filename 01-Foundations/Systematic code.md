---
title: "Systematic code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Systematic_code"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Systematic code

In coding theory, a systematic code is any error-correcting code in which the input data are embedded in the encoded output. Conversely, in a non-systematic code the output does not contain the input symbols.
Systematic codes have the advantage that the parity data can simply be appended to the source block, and receivers do not need to recover the original source symbols if received correctly – this is useful for example if error-correction coding is combined with a hash function for quickly determining the correctness of the received source symbols, or in cases where errors occur in erasures and a received symbol is thus always correct. Furthermore, for engineering purposes such as synchronization and monitoring, it is desirable to get reasonable good estimates of the received source symbols without going through the lengthy decoding process which may be carried out at a remote site at a later time.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Systematic_code