---
title: "Galerkin method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Galerkin_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Galerkin method

In mathematics, in the area of numerical analysis, Galerkin methods are a family of methods for converting a continuous operator problem, such as a differential equation, commonly in a weak formulation, to a discrete problem by applying linear constraints determined by finite sets of basis functions. They are named after the Soviet mathematician Boris Galerkin.
Often when referring to a Galerkin method, one also gives the name along with typical assumptions and approximation methods used:

Ritz–Galerkin method (after Walther Ritz) typically assumes symmetric and positive-definite bilinear form in the weak formulation, where the differential equation for a physical system can be formulated via minimization of a quadratic function representing the system energy and the approximate solution is a linear combination of the given set of the basis functions.
Bubnov–Galerkin method (after Ivan Bubnov) does not require the bilinear form to be symmetric and substitutes the energy minimization with orthogonality constraints determined by the same basis functions that are used to approximate the solution. In an operator formulation of the differential equation, Bubnov–Galerkin method can be viewed as applying an orthogonal projection to the operator.
Petrov–Galerkin method (after Georgii I. Petrov) allows using basis functions for orthogonality constraints (called test basis functions) that are different from the basis functions used to approximate the solution. Petrov–Galerkin method can be viewed as an extension of Bubnov–Galerkin method, applying a projection that is not necessarily orthogonal in the operator formulation of the differential equation.
Examples of Galerkin methods are:

the Galerkin method of weighted residuals, the most common method of calculating the global stiffness matrix in the finite element method,
the boundary element method for solving integral equations,
Krylov subspace methods.

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

- Wikipedia: https://en.wikipedia.org/wiki/Galerkin_method