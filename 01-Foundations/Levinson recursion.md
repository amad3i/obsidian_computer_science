---
title: "Levinson recursion"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Levinson_recursion"
wikipedia_categories: ["Matrices (mathematics)", "Numerical analysis"]
related: ["[[Condition number]]", "[[Matrix analysis]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]"]
---

# Levinson recursion

Levinson recursion or Levinson–Durbin recursion is a procedure in linear algebra to recursively calculate the solution to an equation involving a Toeplitz matrix. The algorithm runs in Θ(n2) time, which is a strong improvement over Gauss–Jordan elimination, which runs in Θ(n3).
The Levinson–Durbin algorithm was proposed first by Norman Levinson in 1947, improved by James Durbin in 1960, and subsequently improved to 4n2 and then 3n2 multiplications by W. F. Trench and S. Zohar, respectively.
Other methods to process data include Schur decomposition and Cholesky decomposition. In comparison to these, Levinson recursion (particularly split Levinson recursion) tends to be faster computationally, but more sensitive to computational inaccuracies like round-off errors.
The Bareiss algorithm for Toeplitz matrices (not to be confused with the general Bareiss algorithm) runs about as fast as Levinson recursion, but it uses O(n2) space, whereas Levinson recursion uses only O(n) space.  The Bareiss algorithm, though, is numerically stable, whereas Levinson recursion is at best only weakly stable (i.e. it exhibits numerical stability for well-conditioned linear systems).
Newer algorithms, called asymptotically fast or sometimes superfast Toeplitz algorithms, can solve in Θ(n (log n)p) for various p (e.g. p = 2, p = 3). Levinson recursion remains popular for several reasons; for one, it is relatively easy to understand in comparison; for another, it can be faster than a superfast algorithm for small n (usually n < 256).

## Related

- [[Condition number]]
- [[Matrix analysis]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Levinson_recursion