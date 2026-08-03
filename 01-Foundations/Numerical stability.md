---
title: "Numerical stability"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Numerical_stability"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Numerical stability

In the mathematical subfield of numerical analysis, numerical stability is a generally desirable property of numerical algorithms. The precise definition of stability depends on the context: one important context is numerical linear algebra, and another is algorithms for solving ordinary and partial differential equations by discrete approximation.
In numerical linear algebra, the principal concern is instabilities caused by proximity to singularities of various kinds, such as very small or nearly colliding eigenvalues. On the other hand, in numerical algorithms for differential equations the concern is the growth of round-off errors and/or small fluctuations in initial data which might cause a large deviation of final answer from the exact solution.
Some numerical algorithms may damp out the small fluctuations (errors) in the input data; others might magnify such errors.  Calculations that can be proven not to magnify approximation errors are called numerically stable.  One of the common tasks of numerical analysis is to try to select algorithms which are robust – that is to say, do not produce a wildly different result for a very small change in the input data.
An opposite phenomenon is instability. Typically, an algorithm involves an approximative method, and in some cases one could prove that the algorithm would approach the right solution in some limit (when using actual real numbers, not floating point numbers). Even in this case, there is no guarantee that it would converge to the correct solution, because the floating-point round-off or truncation errors can be magnified, instead of damped, causing the deviation from the exact solution to grow exponentially.

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

- Wikipedia: https://en.wikipedia.org/wiki/Numerical_stability