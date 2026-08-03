---
title: "Optimal projection equations"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Optimal_projection_equations"
wikipedia_categories: ["Control theory", "Optimal control", "Stochastic control"]
related: ["[[Bellman pseudospectral method]]", "[[Chebyshev pseudospectral method]]", "[[Flat pseudospectral method]]", "[[Legendre pseudospectral method]]", "[[Microgrid]]", "[[Pseudospectral knotting method]]", "[[Robust control]]", "[[Ross' π lemma]]", "[[Ross–Fahroo lemma]]", "[[Ross–Fahroo pseudospectral method]]"]
---

# Optimal projection equations

In control theory,  optimal projection equations constitute necessary and sufficient conditions for a locally optimal reduced-order LQG controller.
The linear-quadratic-Gaussian (LQG) control problem is one of the most fundamental optimal control problems. It concerns uncertain linear systems disturbed by additive white Gaussian noise, incomplete state information (i.e. not all the state variables are measured and available for feedback) also disturbed by additive white Gaussian noise and quadratic costs. Moreover, the solution is unique and constitutes a linear dynamic feedback control law that is easily computed and implemented. Finally the LQG controller is also fundamental to the optimal perturbation control of non-linear systems.
The LQG controller itself is a dynamic system like the system it controls. Both systems have the same state dimension. Therefore, implementing the LQG controller may be problematic if the dimension of the system state is large. The reduced-order LQG problem (fixed-order LQG problem) overcomes this by fixing a-priori the number of states of the LQG controller. This problem is more difficult to solve because it is no longer separable. Also the solution is no longer unique. Despite these facts numerical algorithms are available  to solve the associated optimal projection equations.

## Related

- [[Bellman pseudospectral method]]
- [[Chebyshev pseudospectral method]]
- [[Flat pseudospectral method]]
- [[Legendre pseudospectral method]]
- [[Microgrid]]
- [[Pseudospectral knotting method]]
- [[Robust control]]
- [[Ross' π lemma]]
- [[Ross–Fahroo lemma]]
- [[Ross–Fahroo pseudospectral method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Optimal_projection_equations