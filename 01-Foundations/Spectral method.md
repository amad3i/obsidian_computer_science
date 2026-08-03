---
title: "Spectral method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Spectral_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Spectral method

Spectral methods are a class of techniques used in applied mathematics and scientific computing to numerically solve certain differential equations. The idea is to write the solution of the differential equation as a sum of certain "basis functions" (for example, as a Fourier series which is a sum of sinusoids) and then to choose the coefficients in the sum in order to satisfy the differential equation as well as possible.
Spectral methods and finite-element methods are closely related and built on the same ideas; the main difference between them is that spectral methods use basis functions that are generally nonzero over the whole domain, while finite element methods use basis functions that are nonzero only on small subdomains (compact support). Consequently, spectral methods connect variables globally while finite elements do so locally. Partially for this reason, spectral methods have excellent error properties, with the so-called "exponential convergence" being the fastest possible, when the solution is smooth. However, there are no known three-dimensional single-domain spectral shock capturing results (shock waves are not smooth). In the finite-element community, a method where the degree of the elements is very high or increases as the grid parameter h increases is sometimes called a spectral-element method.
Spectral methods can be used to solve differential equations (PDEs, ODEs, eigenvalue, etc)   and optimization problems. When applying spectral methods to time-dependent PDEs, the solution is typically written as a sum of basis functions with time-dependent coefficients; substituting this in the PDE yields a system of ODEs in the coefficients which can be solved using any numerical method for ODEs. Eigenvalue problems for ODEs are similarly converted to matrix eigenvalue problems .
Spectral methods were developed in a long series of papers by Steven Orszag starting in 1969 including, but not limited to, Fourier series methods for periodic geometry problems, polynomial spectral methods for finite and unbounded geometry problems, pseudospectral methods for highly nonlinear problems, and spectral iteration methods for fast solution of steady-state problems. The implementation of the spectral method is normally accomplished either with collocation or a Galerkin or a Tau approach . For very small problems, the spectral method is unique in that solutions may be written out symbolically, yielding a practical alternative to series solutions for differential equations.
Spectral methods can be computationally less expensive and easier to implement than finite element methods; they shine best when high accuracy is sought in simple domains with smooth solutions. However, because of their global nature, the matrices associated with step computation are dense and computational efficiency will quickly suffer when there are many degrees of freedom (with some exceptions, for example if matrix applications can be written as Fourier transforms). For larger problems and nonsmooth solutions, finite elements will generally work better due to sparse matrices and better modelling of discontinuities and sharp bends.

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

- Wikipedia: https://en.wikipedia.org/wiki/Spectral_method