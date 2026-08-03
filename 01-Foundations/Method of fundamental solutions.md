---
title: "Method of fundamental solutions"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Method_of_fundamental_solutions"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Method of fundamental solutions

In scientific computation and simulation, the method of fundamental solutions (MFS) is a technique for solving partial differential equations based on using the fundamental solution as a basis function. The MFS was developed to overcome the major drawbacks in the boundary element method (BEM) which also uses the fundamental solution to satisfy the governing equation. Consequently, both the MFS and the BEM are of a boundary discretization numerical technique and reduce the computational complexity by one dimensionality and have particular edge over the domain-type numerical techniques such as the finite element and finite volume methods on the solution of infinite domain, thin-walled structures, and inverse problems. 
In contrast to the BEM, the MFS avoids the numerical integration of singular fundamental solution and is an inherent meshfree method. The method, however, is compromised by requiring a controversial fictitious boundary outside the physical domain to circumvent the singularity of fundamental solution, which has seriously restricted its applicability to real-world problems. But nevertheless the MFS has been found very competitive to some application areas such as infinite domain problems.    
The MFS is also known by different names in the literature, including the charge simulation method, the superposition method, the desingularized method, the indirect boundary element method and the virtual boundary element method.

## Related

- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]
- [[Boundary particle method]]
- [[Composite methods for structural dynamics]]
- [[Deep backward stochastic differential equation method]]
- [[Discrete calculus]]
- [[Dormand–Prince method]]
- [[Exponential integrator]]
- [[Fast multipole method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Method_of_fundamental_solutions