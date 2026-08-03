---
title: "Dormand–Prince method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dormand–Prince_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations", "Runge–Kutta methods"]
related: ["[[Runge–Kutta methods]]", "[[Runge–Kutta–Fehlberg method]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Exponential integrator]]"]
---

# Dormand–Prince method

In numerical analysis, the Dormand–Prince (RKDP) method or DOPRI method, is an embedded method for solving ordinary differential equations (ODE). The method is a member of the Runge–Kutta family of ODE solvers. More specifically, it uses six function evaluations to calculate fourth- and fifth-order accurate solutions. The difference between these solutions is then taken to be the error of the (fourth-order) solution. This error estimate is very convenient for adaptive stepsize integration algorithms. Other similar integration methods are Fehlberg (RKF) and Cash–Karp (RKCK).
The Dormand–Prince method has seven stages, but it uses only six function evaluations per step because it has the "First Same As Last" (FSAL) property: the last stage is evaluated at the same point as the first stage of the next step. Dormand and Prince chose the coefficients of their method to minimize the error of the fifth-order solution. This is the main difference with the Fehlberg method, which was constructed so that the fourth-order solution has a small error. For this reason, the Dormand–Prince method is more suitable when the higher-order solution is used to continue the integration, a practice known as local extrapolation.

## Related

- [[Runge–Kutta methods]]
- [[Runge–Kutta–Fehlberg method]]
- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]
- [[Boundary particle method]]
- [[Composite methods for structural dynamics]]
- [[Deep backward stochastic differential equation method]]
- [[Discrete calculus]]
- [[Exponential integrator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dormand–Prince_method