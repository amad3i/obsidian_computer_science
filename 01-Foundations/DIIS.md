---
title: "DIIS"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/DIIS"
wikipedia_categories: ["Computational chemistry", "Numerical linear algebra", "Quantum chemistry"]
related: ["[[1s Slater-type function]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[Car–Parrinello molecular dynamics]]", "[[CHELPG]]", "[[Coulomb operator]]", "[[Diffusion Monte Carlo]]", "[[Distributed multipole analysis]]", "[[Energy level]]", "[[Fermi resonance]]"]
---

# DIIS

DIIS (direct inversion in the iterative subspace or direct inversion of the iterative subspace), also known as Pulay mixing, is a technique for extrapolating the solution to a set of linear equations by directly minimizing an error residual (e.g. a Newton–Raphson step size) with respect to a linear combination of known sample vectors. DIIS was developed by Peter Pulay in the field of computational quantum chemistry with the intent to accelerate and stabilize the convergence of the Hartree–Fock self-consistent field method.
At a given iteration, the approach constructs a linear combination of approximate error vectors from previous iterations. The coefficients of the linear combination are determined so to best approximate, in a least squares sense, the null vector. The newly determined coefficients are then used to extrapolate the function variable for the next iteration.
The method has been shown to be equivalent to the pre-existing Anderson acceleration, and to reduce to GMRES in the linear case.

## Related

- [[1s Slater-type function]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[Car–Parrinello molecular dynamics]]
- [[CHELPG]]
- [[Coulomb operator]]
- [[Diffusion Monte Carlo]]
- [[Distributed multipole analysis]]
- [[Energy level]]
- [[Fermi resonance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DIIS