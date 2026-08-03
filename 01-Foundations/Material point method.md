---
title: "Material point method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Material_point_method"
wikipedia_categories: ["Computational fluid dynamics", "Computational mathematics", "Numerical analysis", "Numerical differential equations", "Simulation"]
related: ["[[Momentum mapping format]]", "[[Natural element method]]", "[[Finite volume method]]", "[[Mesh generation]]", "[[Meshfree methods]]", "[[Particle method]]", "[[Weakened weak form]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]"]
---

# Material point method

The material point method (MPM) is a numerical technique used to simulate the behavior of solids, liquids, gases, and any other continuum material. Especially, it is a robust spatial discretization method for simulating multi-phase (solid-fluid-gas) interactions. In the MPM, a continuum body is described by a number of small Lagrangian elements referred to as 'material points'. These material points are surrounded by a background mesh/grid that is used to calculate terms such as the deformation gradient. Unlike other mesh-based methods like the finite element method, finite volume method or finite difference method, the MPM is not a mesh based method and is instead categorized as a meshless/meshfree or continuum-based particle method, examples of which are smoothed particle hydrodynamics and peridynamics. Despite the presence of a background mesh, the MPM does not encounter the drawbacks of mesh-based methods (high deformation tangling, advection errors etc.) which makes it a promising and powerful tool in computational mechanics.
The MPM was originally proposed, as an extension of a similar method known as FLIP (a further extension of a method called PIC) to computational solid dynamics, in the early 1990 by Professors Deborah L. Sulsky, Zhen Chen and Howard L. Schreyer at University of New Mexico. After this initial development, the MPM has been further developed both in the national labs as well as the University of New Mexico, Oregon State University, University of Utah and more across the US and the world. Recently the number of institutions researching the MPM has been growing with added popularity and awareness coming from various sources such as the MPM's use in the Disney film Frozen.

## Related

- [[Momentum mapping format]]
- [[Natural element method]]
- [[Finite volume method]]
- [[Mesh generation]]
- [[Meshfree methods]]
- [[Particle method]]
- [[Weakened weak form]]
- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Material_point_method