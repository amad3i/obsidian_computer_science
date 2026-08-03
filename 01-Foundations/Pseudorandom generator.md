---
title: "Pseudorandom generator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Pseudorandom_generator"
wikipedia_categories: ["Algorithmic information theory", "Cryptography", "Pseudorandomness"]
related: ["[[Pseudorandom ensemble]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Algorithmic information theory]]", "[[Algorithmic probability]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]"]
---

# Pseudorandom generator

In theoretical computer science and cryptography, a pseudorandom generator (PRG) for a class of statistical tests is a deterministic procedure that maps a random seed to a longer pseudorandom string such that no statistical test in the class can distinguish between the output of the generator and the uniform distribution. The random seed itself is typically a short binary string drawn from the uniform distribution.
Many different classes of statistical tests have been considered in the literature, among them the class of all Boolean circuits of a given size.
It is not known whether good pseudorandom generators for this class exist, but it is known that their existence is in a certain sense equivalent to (unproven) circuit lower bounds in computational complexity theory.
Hence the construction of pseudorandom generators for the class of Boolean circuits of a given size rests on currently unproven hardness assumptions.

## Related

- [[Pseudorandom ensemble]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Algorithmic information theory]]
- [[Algorithmic probability]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pseudorandom_generator