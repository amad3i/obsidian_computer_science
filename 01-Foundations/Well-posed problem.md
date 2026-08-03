---
title: "Well-posed problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Well-posed_problem"
wikipedia_categories: ["Numerical analysis", "Partial differential equations"]
related: ["[[Bidomain model]]", "[[Calderón projector]]", "[[Forward problem of electrocardiology]]", "[[Integrable algorithm]]", "[[Multigrid method]]", "[[Partial differential algebraic equation]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]"]
---

# Well-posed problem

In mathematics, the solution to a well-posed problem satisfies the following properties:

It exists;
It is unique;
Its behavior changes continuously with the auxiliary conditions, such as initial or boundary values.
These criteria were first introduced by Jacques Hadamard in 1902.
Examples of archetypal well-posed problems include the Dirichlet problem for Laplace's equation, and the heat equation with specified initial conditions. These might be regarded as 'natural' problems in that there are physical processes modeled by these problems.
Problems that are not well-posed in the sense above are termed ill-posed.  A simple example is a global optimization problem, because the location of the optima is generally not a continuous function of the parameters specifying the objective, even when the objective itself is a smooth function of those parameters. Inverse problems are often ill-posed; for example, the inverse heat equation, deducing a previous distribution of temperature from final data, is not well-posed in that the solution is highly sensitive to changes in the final data.
Continuum models must often be discretized in order to obtain a numerical solution. While solutions may be continuous with respect to the initial conditions, they may suffer from numerical instability when solved with finite precision, or with errors in the data.

## Related

- [[Bidomain model]]
- [[Calderón projector]]
- [[Forward problem of electrocardiology]]
- [[Integrable algorithm]]
- [[Multigrid method]]
- [[Partial differential algebraic equation]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Well-posed_problem