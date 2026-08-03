---
title: "CORDIC"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/CORDIC"
wikipedia_categories: ["Computer arithmetic", "Digit-by-digit algorithms", "Numerical analysis", "Root-finding algorithms", "Shift-and-add algorithms", "Trigonometry"]
related: ["[[2Sum]]", "[[Gal's accurate tables]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[INTLAB]]", "[[Kahan summation algorithm]]", "[[Karlsruhe Accurate Arithmetic]]", "[[Numerical error]]", "[[Pairwise summation]]", "[[Sterbenz lemma]]"]
---

# CORDIC

CORDIC, short for coordinate rotation digital computer, is a simple and efficient algorithm to calculate trigonometric functions, hyperbolic functions, square roots, multiplications, divisions, exponentials, and logarithms with arbitrary base, typically converging with one digit (or bit) per iteration. CORDIC is therefore an example of a digit-by-digit algorithm. The original system is sometimes referred to as Volder's algorithm.
CORDIC and closely related methods known as pseudo-multiplication and pseudo-division or factor combining are commonly used when no hardware multiplier is available (e.g. in simple microcontrollers and field-programmable gate arrays or FPGAs), as the only operations they require are addition, subtraction, bitshift and lookup tables. As such, they all belong to the class of shift-and-add algorithms. In computer science, CORDIC is often used to implement floating-point arithmetic when the target platform lacks the hardware to multiply for cost or space reasons. This was the case for most early microcomputers based on processors like the MOS 6502 and Zilog Z80.
Over the years, a number of variations on the concept emerged, including circular CORDIC (Jack E. Volder), linear CORDIC, hyperbolic CORDIC (John Stephen Walther), and generalized hyperbolic CORDIC (GH CORDIC) (Yuanyong Luo et al.),

## Related

- [[2Sum]]
- [[Gal's accurate tables]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[INTLAB]]
- [[Kahan summation algorithm]]
- [[Karlsruhe Accurate Arithmetic]]
- [[Numerical error]]
- [[Pairwise summation]]
- [[Sterbenz lemma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CORDIC