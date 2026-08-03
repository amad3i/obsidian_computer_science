---
title: "Backtracking line search"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Backtracking_line_search"
wikipedia_categories: ["Mathematical optimization", "Optimization algorithms and methods"]
related: ["[[Barzilai–Borwein method]]", "[[Gradient descent]]", "[[Least-squares spectral analysis]]", "[[Subgradient method]]", "[[Algorithmic problems on convex sets]]", "[[Alpha–beta pruning]]", "[[Analysis of Boolean functions]]", "[[Ant colony optimization algorithms]]", "[[Automatic label placement]]", "[[Basis pursuit]]"]
---

# Backtracking line search

In (unconstrained) mathematical optimization, a backtracking line search is a line search method to determine the amount to move along a given search direction. Its use requires that the objective function is differentiable and that its gradient is known.
The method involves starting with a relatively large estimate of the step size for movement along the line search direction, and iteratively shrinking the step size (i.e., "backtracking") until a decrease of the objective function is observed that adequately corresponds to the amount of decrease that is expected, based on the step size and the local gradient of the objective function. A common stopping criterion is the Armijo–Goldstein condition.
Backtracking line search is typically used for gradient descent (GD), but it can also be used in other contexts. For example, it can be used with Newton's method if the Hessian matrix is positive definite.

## Related

- [[Barzilai–Borwein method]]
- [[Gradient descent]]
- [[Least-squares spectral analysis]]
- [[Subgradient method]]
- [[Algorithmic problems on convex sets]]
- [[Alpha–beta pruning]]
- [[Analysis of Boolean functions]]
- [[Ant colony optimization algorithms]]
- [[Automatic label placement]]
- [[Basis pursuit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Backtracking_line_search