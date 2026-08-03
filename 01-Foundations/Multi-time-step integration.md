---
title: "Multi-time-step integration"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-time-step_integration"
wikipedia_categories: ["Applied mathematics", "Numerical analysis"]
related: ["[[Discrete calculus]]", "[[Discretization]]", "[[Explicit algebraic stress model]]", "[[Grossone]]", "[[Integrable algorithm]]", "[[Least-squares spectral analysis]]", "[[Scarborough criterion]]", "[[Stiffness matrix]]", "[[2Sum]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]"]
---

# Multi-time-step integration

In numerical analysis, multi-time-step integration, also referred to as multiple-step or asynchronous time integration, is a numerical time-integration method that uses different time-steps or time-integrators for different parts of the problem. There are different approaches to multi-time-step integration. They are based on domain decomposition and can be classified into strong (monolithic) or weak (staggered) schemes. Using different time-steps or time-integrators in the context of a weak algorithm is rather straightforward, because the numerical solvers operate independently. However, this is not the case in a strong algorithm. In the past few years a number of research articles have addressed the development of strong multi-time-step algorithms. In either case, strong or weak, the numerical accuracy and stability needs to be carefully studied. Other approaches to multi-time-step integration in the context of operator splitting methods have also been developed; i.e., multi-rate GARK method and multi-step methods for molecular dynamics simulations.

## Related

- [[Discrete calculus]]
- [[Discretization]]
- [[Explicit algebraic stress model]]
- [[Grossone]]
- [[Integrable algorithm]]
- [[Least-squares spectral analysis]]
- [[Scarborough criterion]]
- [[Stiffness matrix]]
- [[2Sum]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-time-step_integration