---
title: "Subgradient method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Subgradient_method"
wikipedia_categories: ["Convex analysis", "Convex optimization", "Mathematical optimization", "Optimization algorithms and methods"]
related: ["[[Convex optimization]]", "[[Algorithmic problems on convex sets]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Gradient descent]]", "[[Least-squares spectral analysis]]", "[[Maximum theorem]]", "[[Normal cone (convex analysis)]]", "[[Separation oracle]]", "[[Absolutely convex set]]"]
---

# Subgradient method

Subgradient methods are convex optimization methods which use subderivatives. Originally developed by Naum Z. Shor and others in the 1960s and 1970s, subgradient methods are convergent when applied even to a non-differentiable objective function. When the objective function is differentiable, subgradient methods for unconstrained problems use the same search direction as the method of gradient descent.
Subgradient methods are slower than Newton's method when applied to minimize twice continuously differentiable convex functions. However, Newton's method fails to converge on problems that have non-differentiable kinks.
In recent years, some interior-point methods have been suggested for convex minimization problems, but subgradient projection methods and related bundle methods of descent remain competitive. For convex minimization problems with very large number of dimensions, subgradient-projection methods are suitable, because they require little storage.
Subgradient projection methods are often applied to large-scale problems with decomposition techniques. Such decomposition methods often allow a simple distributed method for a problem.

## Related

- [[Convex optimization]]
- [[Algorithmic problems on convex sets]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Gradient descent]]
- [[Least-squares spectral analysis]]
- [[Maximum theorem]]
- [[Normal cone (convex analysis)]]
- [[Separation oracle]]
- [[Absolutely convex set]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Subgradient_method