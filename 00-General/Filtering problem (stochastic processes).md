---
title: "Filtering problem (stochastic processes)"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Filtering_problem_(stochastic_processes)"
wikipedia_categories: ["Control theory", "Signal estimation", "Stochastic differential equations"]
related: ["[[Kalman filter]]", "[[Projection filters]]", "[[Switching Kalman filter]]", "[[Bellman filter]]", "[[Covariance intersection]]", "[[Moving horizon estimation]]", "[[Unscented transform]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]"]
---

# Filtering problem (stochastic processes)

In the theory of stochastic processes, filtering describes the problem of determining the state of a system from an incomplete and potentially noisy set of observations. For example, in GPS navigation, filtering helps estimate a car’s true position (the state) from noisy satellite signals (the observations). While originally motivated by problems in engineering, filtering found applications in many fields from signal processing to finance.
The problem of optimal non-linear filtering (even for the non-stationary case) was solved by Ruslan L. Stratonovich (1959, 1960), see also Harold J. Kushner's work  and Moshe Zakai's, who introduced a simplified dynamics for the unnormalized conditional law of the filter known as the Zakai equation.  The solution, however, is infinite-dimensional in the general case. Certain approximations and special cases are well understood: for example, the linear filters are optimal for Gaussian random variables, and are known as the Wiener filter and the Kalman-Bucy filter. More generally, as the solution is infinite dimensional, it requires finite dimensional approximations to be implemented in a computer with finite memory. A finite dimensional approximated nonlinear filter may be more based on heuristics, such as the extended Kalman filter or the assumed density filters, or more methodologically oriented such as for example the projection filters, some sub-families of which are shown to coincide with the assumed density filters. 
Particle filters are another option to attack the infinite dimensional filtering problem and are based on   sequential Monte Carlo methods.
In general, if the separation principle applies, then filtering also arises as part of the solution of an optimal control problem. For example, the Kalman filter is the estimation part of the optimal control solution to the linear-quadratic-Gaussian control problem.

## Related

- [[Kalman filter]]
- [[Projection filters]]
- [[Switching Kalman filter]]
- [[Bellman filter]]
- [[Covariance intersection]]
- [[Moving horizon estimation]]
- [[Unscented transform]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Filtering_problem_(stochastic_processes)