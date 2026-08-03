---
title: "Local linearization method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_linearization_method"
wikipedia_categories: ["Numerical analysis", "Numerical integration"]
related: ["[[Boole's rule]]", "[[Numerical integration]]", "[[Nyström method]]", "[[Simpson's rule]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]"]
---

# Local linearization method

In numerical analysis, the local linearization (LL) method is a general strategy for designing numerical integrators for differential equations based on a local (piecewise) linearization of the given equation on consecutive time intervals. The numerical integrators are then iteratively defined as the solution of the resulting piecewise linear equation at the end of each consecutive interval. The LL method has been developed for a variety of equations such as the ordinary, delayed, random and stochastic differential equations. The LL integrators are key component in the implementation of inference methods for the estimation of unknown parameters and unobserved variables of differential equations given time series of (potentially noisy) observations. The LL schemes are ideals to deal with complex models in a variety of fields as  neuroscience, finance, forestry management, control engineering, mathematical statistics, etc.

## Related

- [[Boole's rule]]
- [[Numerical integration]]
- [[Nyström method]]
- [[Simpson's rule]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_linearization_method