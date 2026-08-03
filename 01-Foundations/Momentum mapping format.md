---
title: "Momentum mapping format"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Momentum_mapping_format"
wikipedia_categories: ["Civil engineering", "Computational fluid dynamics", "Computational mathematics", "Computational physics", "Materials science", "Numerical analysis", "Numerical differential equations", "Simulation"]
related: ["[[Material point method]]", "[[Natural element method]]", "[[Finite volume method]]", "[[Mesh generation]]", "[[Meshfree methods]]", "[[Particle method]]", "[[Weakened weak form]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]"]
---

# Momentum mapping format

Momentum mapping format is a key technique in the material point method (MPM) for transferring physical quantities such as momentum, mass, and stress between a material point and a background grid.
The material point method is a numerical technique using a mixed Eulerian-Lagrangian description. It discretizes the computational domain with material points and employs a background grid to solve the momentum equations. Proposed by Sulsky et al. in 1994.
MPM has since been expanded to various fields such as computational solid dynamics. Currently, MPM features several momentum mapping schemes, with the four main ones being PIC (particle-in-cell), FLIP (fluid-implicit particle), hybrid format, and APIC (affine particle-in-cell). Understanding these schemes in-depth is crucial for the further development of MPM.

## Related

- [[Material point method]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Momentum_mapping_format