---
title: "Estrin's scheme"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Estrin's_scheme"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Estrin's scheme

In numerical analysis, Estrin's scheme (after Gerald Estrin), also known as Estrin's method, is an algorithm for numerical evaluation of polynomials.
Horner's method for evaluation of polynomials is one of the most commonly used algorithms for this purpose, and unlike Estrin's scheme it is optimal in the sense that it minimizes the number of multiplications and additions required to evaluate an arbitrary polynomial.  However, each operation depends on the previous one, so it cannot take advantage of modern processors' ability to perform multiple independent operations in parallel.  Estrin's scheme is one method which attempts to overcome this serialization while still being reasonably close to optimal.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Estrin's_scheme