---
title: "Pseudo-polynomial time"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Pseudo-polynomial_time"
wikipedia_categories: ["Analysis of algorithms", "Complexity classes", "Computational complexity theory", "Pseudo-polynomial time algorithms"]
related: ["[[Quasi-polynomial time]]", "[[Analysis of algorithms]]", "[[Best, worst and average case]]", "[[Combinatorial search]]", "[[Complexity class]]", "[[Computational complexity]]", "[[Half-exponential function]]", "[[Klee–Minty cube]]", "[[Pseudo-polynomial transformation]]", "[[Smoothed analysis]]"]
---

# Pseudo-polynomial time

In computational complexity theory, a numeric algorithm runs in pseudo-polynomial time if its running time is bounded from above by a polynomial function of the two variables: the numeric value of the input (the largest integer present in the input) and the length of the input (the number of bits required to represent it).
In general, using a positional number system, the numeric value of the input is exponential in the input length, which is why a pseudo-polynomial time algorithm does not necessarily run in polynomial time with respect to the input length.
The distinction between the value of a number and its length is due to positional encoding; if numeric inputs are instead encoded in unary then the length and value are the same.
An NP-complete problem with known pseudo-polynomial time algorithms is called weakly NP-complete.
An NP-complete problem is called strongly NP-complete if it is proven that it cannot be solved by a  pseudo-polynomial time algorithm unless P = NP. The strong/weak kinds of NP-hardness are defined analogously.

## Related

- [[Quasi-polynomial time]]
- [[Analysis of algorithms]]
- [[Best, worst and average case]]
- [[Combinatorial search]]
- [[Complexity class]]
- [[Computational complexity]]
- [[Half-exponential function]]
- [[Klee–Minty cube]]
- [[Pseudo-polynomial transformation]]
- [[Smoothed analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pseudo-polynomial_time