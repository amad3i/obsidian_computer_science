---
title: "Runge–Kutta–Fehlberg method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Runge–Kutta–Fehlberg_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations", "Runge–Kutta methods"]
related: ["[[Dormand–Prince method]]", "[[Runge–Kutta methods]]", "[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Exponential integrator]]"]
---

# Runge–Kutta–Fehlberg method

In mathematics, the Runge–Kutta–Fehlberg method (or Fehlberg method) is an algorithm in numerical analysis for the numerical solution of ordinary differential equations. It was developed by the German mathematician Erwin Fehlberg and is based on the large class of Runge–Kutta methods.
The novelty of Fehlberg's method is that it is an embedded method from the Runge–Kutta family, meaning that it reuses the same intermediate calculations to produce two estimates of different accuracy, allowing for automatic error estimation. The method presented in Fehlberg's 1969 paper has been dubbed the RKF45 method, and is a method of order O(h4) with an error estimator of order O(h5). By performing one extra calculation, the error in the solution can be estimated and controlled by using the higher-order embedded method that allows for an adaptive stepsize to be determined automatically.

## Related

- [[Dormand–Prince method]]
- [[Runge–Kutta methods]]
- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]
- [[Boundary particle method]]
- [[Composite methods for structural dynamics]]
- [[Deep backward stochastic differential equation method]]
- [[Discrete calculus]]
- [[Exponential integrator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Runge–Kutta–Fehlberg_method