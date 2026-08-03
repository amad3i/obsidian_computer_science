---
title: "Linear multistep method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Linear_multistep_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Linear multistep method

Linear multistep methods are used for the numerical solution of ordinary differential equations. Conceptually, a numerical method starts from an initial point and then takes a short step forward in time to find the next solution point. The process continues with subsequent steps to map out the solution. Single-step methods (such as Euler's method) refer to only one previous point and its derivative to determine the current value. Methods such as Runge–Kutta take some intermediate steps (for example, a half-step) to obtain a higher order method, but then discard all previous information before taking a second step. Multistep methods attempt to gain efficiency by keeping and using the information from previous steps rather than discarding it. Consequently, multistep methods refer to several previous points and derivative values. In the case of linear multistep methods, a linear combination of the previous points and derivative values is used.

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

- Wikipedia: https://en.wikipedia.org/wiki/Linear_multistep_method