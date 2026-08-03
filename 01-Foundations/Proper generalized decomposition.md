---
title: "Proper generalized decomposition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Proper_generalized_decomposition"
wikipedia_categories: ["Boundary value problems", "Dimension reduction", "Mathematical modeling", "Numerical analysis"]
related: ["[[Bidomain model]]", "[[Bueno-Orovio–Cherry–Fenton model]]", "[[Forward problem of electrocardiology]]", "[[Iterative rational Krylov algorithm]]", "[[Model order reduction]]", "[[Movable cellular automaton]]", "[[Surrogate model]]", "[[Variational multiscale method]]", "[[Vector field reconstruction]]", "[[2Sum]]"]
---

# Proper generalized decomposition

The proper generalized decomposition (PGD) is an iterative numerical method for solving boundary value problems (BVPs), that is, partial differential equations constrained by a set of boundary conditions, such as the Poisson's equation or the Laplace's equation.
The PGD algorithm computes an approximation of the solution of the BVP by successive enrichment. This means that, in each iteration, a new component (or mode) is computed and added to the approximation. In principle, the more modes obtained, the closer the approximation is to its theoretical solution. Unlike POD principal components, PGD modes are not necessarily orthogonal to each other.
By selecting only the most relevant PGD modes, a reduced order model of the solution is obtained. Because of this, PGD is considered a dimensionality reduction algorithm.

## Related

- [[Bidomain model]]
- [[Bueno-Orovio–Cherry–Fenton model]]
- [[Forward problem of electrocardiology]]
- [[Iterative rational Krylov algorithm]]
- [[Model order reduction]]
- [[Movable cellular automaton]]
- [[Surrogate model]]
- [[Variational multiscale method]]
- [[Vector field reconstruction]]
- [[2Sum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Proper_generalized_decomposition