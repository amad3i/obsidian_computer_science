---
title: "Moving horizon estimation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Moving_horizon_estimation"
wikipedia_categories: ["Control theory", "Linear filters", "Nonlinear filters", "Signal estimation"]
related: ["[[Covariance intersection]]", "[[Kalman filter]]", "[[Switching Kalman filter]]", "[[Unscented transform]]", "[[Bellman filter]]", "[[Projection filters]]", "[[Filtering problem (stochastic processes)]]", "[[Particle filter]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]"]
---

# Moving horizon estimation

Moving horizon estimation (MHE) is an optimization approach that uses a series of measurements observed over time, containing noise (random variations) and other inaccuracies, and produces estimates of unknown variables or parameters. Unlike deterministic approaches, MHE requires an iterative approach that relies on linear programming or nonlinear programming solvers to find a solution.
MHE reduces to the Kalman filter under certain simplifying conditions. A critical evaluation of the extended Kalman filter and the MHE found that the MHE improved performance at the cost of increased computational expense. Because of the computational expense, MHE has generally been applied to systems where there are greater computational resources and moderate to slow system dynamics. However, in the literature there are some methods to accelerate this method.

## Related

- [[Covariance intersection]]
- [[Kalman filter]]
- [[Switching Kalman filter]]
- [[Unscented transform]]
- [[Bellman filter]]
- [[Projection filters]]
- [[Filtering problem (stochastic processes)]]
- [[Particle filter]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Moving_horizon_estimation