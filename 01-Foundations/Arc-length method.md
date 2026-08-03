---
title: "Arc-length method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Arc-length_method"
wikipedia_categories: ["Finite element method", "Numerical analysis", "Structural analysis"]
related: ["[[Applied element method]]", "[[Hermes Project]]", "[[Sheet metal forming simulation]]", "[[Superconvergence]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Approximation]]"]
---

# Arc-length method

In numerical analysis and computational mechanics, the arc-length method, also known as the Riks method, is a numerical method for nonlinear structural analysis in which the structural response does not necessarily increase as the applied load increases, and may instead decrease. By treating both the structural response and the applied load as unknowns, the method enables equilibrium solutions to be continued beyond limit points, at which the applied load changes from increasing to decreasing or vice versa. 
The arc-length method was developed independently by Wempner and Riks in the 1970s and was later reformulated by Crisfield. This method has been implemented in finite element software packages for nonlinear structural analysis such as post-buckling, strain softening, and fracture. Step-length control, root selection criteria, and branch-switching techniques for tracing multiple equilibrium solutions are important aspects of improving the numerical performance of the method.

## Related

- [[Applied element method]]
- [[Hermes Project]]
- [[Sheet metal forming simulation]]
- [[Superconvergence]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Arc-length_method