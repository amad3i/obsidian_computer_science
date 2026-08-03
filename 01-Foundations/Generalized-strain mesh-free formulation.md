---
title: "Generalized-strain mesh-free formulation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalized-strain_mesh-free_formulation"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Generalized-strain mesh-free formulation

The generalized-strain mesh-free (GSMF) formulation is a local meshfree method in the field of numerical analysis, completely integration free, working as a weighted-residual weak-form collocation. This method was first presented by Oliveira and Portela (2016), in order to further improve the computational efficiency of meshfree methods in numerical analysis. Local meshfree methods are derived through a weighted-residual formulation which leads to a local weak form that is the well known work theorem of the theory of structures. In an arbitrary local region, the work theorem establishes an energy relationship between a statically-admissible stress field and an independent kinematically-admissible strain field. Based on the independence of these two fields, this formulation results in a local form of the work theorem that is reduced to regular boundary terms only, integration-free and free of volumetric locking.
Advantages over finite element methods are that GSMF doesn't rely on a grid, and is more precise and faster when solving bi-dimensional problems. When compared to other meshless methods, such as rigid-body displacement mesh-free (RBDMF) formulation, the element-free Galerkin (EFG) and the meshless local Petrov-Galerkin finite volume method (MLPG FVM); GSMF proved to be superior not only regarding the computational efficiency, but also regarding the accuracy.
The moving least squares (MLS) approximation of the elastic field is used on this local meshless formulation.

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

- Wikipedia: https://en.wikipedia.org/wiki/Generalized-strain_mesh-free_formulation