---
title: "Polar code (coding theory)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Polar_code_(coding_theory)"
wikipedia_categories: ["Capacity-achieving codes", "Capacity-approaching codes", "Coding theory", "Error detection and correction"]
related: ["[[Expander code]]", "[[Low-density parity-check code]]", "[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]"]
---

# Polar code (coding theory)

In information theory, polar codes are a linear block error-correcting codes. The code construction is based on a multiple recursive concatenation of a short kernel code which transforms the physical channel into virtual outer channels. When the number of recursions becomes large, the virtual channels tend to either have high reliability or low reliability (in other words, they polarize or become sparse), and the data bits are allocated to the most reliable channels. It is the first code with an explicit construction to provably achieve the channel capacity for symmetric binary-input, discrete, memoryless channels (B-DMC) with polynomial dependence on the gap to capacity. Polar codes were developed by Erdal Arikan, a professor of electrical engineering at Bilkent University.
Notably, polar codes have modest encoding and decoding complexity O(n log n), which renders them attractive for many applications. Moreover, the encoding and decoding energy complexity of generalized polar codes can reach the fundamental lower bounds for energy consumption of two dimensional circuitry to within an O(nε polylog n) factor for any ε > 0.

## Related

- [[Expander code]]
- [[Low-density parity-check code]]
- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Polar_code_(coding_theory)