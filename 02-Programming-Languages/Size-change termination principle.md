---
title: "Size-change termination principle"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Size-change_termination_principle"
wikipedia_categories: ["Static program analysis", "Theory of computation"]
related: ["[[Ackermann function]]", "[[Admissible numbering]]", "[[Alias analysis]]", "[[Andreas Brandstädt]]", "[[Array-access analysis]]", "[[Blockhead (thought experiment)]]", "[[Bremermann's limit]]", "[[Brooks–Iyengar algorithm]]", "[[Busy beaver]]", "[[Byzantine fault]]"]
---

# Size-change termination principle

The size-change termination principle (SCT) guarantees termination for a computer program by proving that infinite computations always trigger infinite descent in data values that are well-founded. Size-change termination analysis utilizes this principle in order to solve the universal halting problem for a certain class of programs. When applied to general programs, the principle is intended to be used conservatively, which means that if the analysis determines that a program is terminating, the answer is sound, but a negative answer means "don't know". The decision problem for SCT is PSPACE-complete; however, there exists an algorithm that computes an approximation of the decision problem in polynomial time. Size-change analysis is applicable to both first-order and higher-order functional programs, as well as imperative programs and logic programs. The latter application preceded by four years the general formulation of the principle by Lee et al.

## Related

- [[Ackermann function]]
- [[Admissible numbering]]
- [[Alias analysis]]
- [[Andreas Brandstädt]]
- [[Array-access analysis]]
- [[Blockhead (thought experiment)]]
- [[Bremermann's limit]]
- [[Brooks–Iyengar algorithm]]
- [[Busy beaver]]
- [[Byzantine fault]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Size-change_termination_principle