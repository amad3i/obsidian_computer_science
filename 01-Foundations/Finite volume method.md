---
title: "Finite volume method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Finite_volume_method"
wikipedia_categories: ["Computational fluid dynamics", "Numerical analysis", "Numerical differential equations"]
related: ["[[Material point method]]", "[[Mesh generation]]", "[[Meshfree methods]]", "[[Momentum mapping format]]", "[[Natural element method]]", "[[Particle method]]", "[[Weakened weak form]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]"]
---

# Finite volume method

The finite volume method (FVM) is a method for representing and evaluating partial differential equations in the form of algebraic equations.
In the finite volume method, volume integrals in a partial differential equation that contain a divergence term are converted to surface integrals, using the divergence theorem. 
These terms are then evaluated as fluxes at the surfaces of each finite volume. Because the flux entering a given volume is identical to that leaving the adjacent volume, these methods are conservative. Another advantage of the finite volume method is that it is easily formulated to allow for unstructured meshes. The method is used in many computational fluid dynamics packages.
"Finite volume" refers to the small volume surrounding each node point on a mesh.
Finite volume methods can be compared and contrasted with the finite difference methods, which approximate derivatives using nodal values, or finite element methods, which create local approximations of a solution using local data, and construct a global approximation by stitching them together. In contrast a finite volume method evaluates exact expressions for the average value of the solution over some volume, and uses this data to construct approximations of the solution within cells.

## Related

- [[Material point method]]
- [[Mesh generation]]
- [[Meshfree methods]]
- [[Momentum mapping format]]
- [[Natural element method]]
- [[Particle method]]
- [[Weakened weak form]]
- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Finite_volume_method