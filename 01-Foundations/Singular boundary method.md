---
title: "Singular boundary method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Singular_boundary_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Singular boundary method

In numerical analysis, the singular boundary method (SBM) belongs to a family of meshless boundary collocation techniques which include the method of fundamental solutions (MFS), boundary knot method (BKM), regularized meshless method (RMM), boundary particle method (BPM), modified MFS, and so on. This family of strong-form collocation methods is designed to avoid singular numerical integration and mesh generation in the traditional boundary element method (BEM) in the numerical solution of boundary value problems with boundary nodes, in which a fundamental solution of the governing equation is explicitly known. 
The salient feature of the SBM is to overcome the fictitious boundary in the method of fundamental solution, while keeping all merits of the latter. The method offers several advantages over the classical domain or boundary discretization methods, among which are:

meshless. The method requires neither domain nor boundary meshing but boundary-only discretization points;
integration-free. The numerical integration of singular or nearly singular kernels could be otherwise troublesome, expensive, and complicated, as in the case, for example, the boundary element method;
boundary-only discretization for homogeneous problems. The SBM shares all the advantages of the BEM over domain discretization methods such as the finite element or finite difference methods;
to overcome the perplexing fictitious boundary in the method of fundamental solutions (see Figs. 1 and 2), thanks to the introduction of the concept of the origin intensity factor, which isolates the singularity of the fundamental solutions.
The SBM provides a significant and promising alternative to popular boundary-type methods such as the BEM and MFS, in particular, for infinite domain, wave, thin-walled structures, and inverse problems.

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

- Wikipedia: https://en.wikipedia.org/wiki/Singular_boundary_method