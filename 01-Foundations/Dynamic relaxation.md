---
title: "Dynamic relaxation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_relaxation"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Dynamic relaxation

Dynamic relaxation is a numerical method, which, among other things, can be used to do "form-finding" for cable and fabric structures. The aim is to find a geometry where all forces are in equilibrium. In the past this was done by direct modelling, using hanging chains and weights (see Gaudi), or by using soap films, which have the property of adjusting to find a "minimal surface".
The dynamic relaxation method is based on discretizing the continuum under consideration by lumping the mass at nodes and defining the relationship between nodes in terms of stiffness (see also the finite element method). The system oscillates about the equilibrium position under the influence of loads. An iterative process is followed by simulating a pseudo-dynamic process in time, with each iteration based on an update of the geometry, similar to leapfrog integration and related to velocity Verlet integration.

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

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_relaxation