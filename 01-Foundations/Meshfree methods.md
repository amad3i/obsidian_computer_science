---
title: "Meshfree methods"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Meshfree_methods"
wikipedia_categories: ["Computational fluid dynamics", "Numerical analysis", "Numerical differential equations"]
related: ["[[Finite volume method]]", "[[Material point method]]", "[[Mesh generation]]", "[[Momentum mapping format]]", "[[Natural element method]]", "[[Particle method]]", "[[Weakened weak form]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]"]
---

# Meshfree methods

In the field of numerical analysis, meshfree methods are those that do not require connection between nodes of the simulation domain, i.e. a mesh, but are rather based on interaction of each node with all its neighbors. As a consequence, original extensive properties such as mass or kinetic energy are no longer assigned to mesh elements but rather to the single nodes. Meshfree methods enable the simulation of some otherwise difficult types of problems, at the cost of extra computing time and programming effort. The absence of a mesh allows Lagrangian simulations, in which the nodes can move according to the velocity field.

## Related

- [[Finite volume method]]
- [[Material point method]]
- [[Mesh generation]]
- [[Momentum mapping format]]
- [[Natural element method]]
- [[Particle method]]
- [[Weakened weak form]]
- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Meshfree_methods