---
title: "Adaptive step size"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Adaptive_step_size"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]", "[[Finite difference]]"]
---

# Adaptive step size

In mathematics and numerical analysis,  an adaptive step size is used in some methods for the numerical solution of ordinary differential equations (including the special case of numerical integration) in order to control the errors of the method and to ensure stability properties such as A-stability. 
Using an adaptive stepsize is of particular importance when there is a large variation in the size of the derivative. 
For example, when modeling the motion of a satellite about the earth as a standard Kepler orbit, a fixed time-stepping method such as the Euler method may be sufficient. 
However things are more difficult if one wishes to model the motion of a spacecraft taking into account both the Earth and the Moon as in the Three-body problem. 
There, scenarios emerge where one can take large time steps when the spacecraft is far from the Earth and Moon, but if the spacecraft gets close to colliding with one of the planetary bodies, then small time steps are needed.  Romberg's method and Runge–Kutta–Fehlberg are examples of a numerical integration methods which use an adaptive stepsize.

## Related

- [[Bi-directional delay line]]
- [[Boundary knot method]]
- [[Boundary particle method]]
- [[Composite methods for structural dynamics]]
- [[Deep backward stochastic differential equation method]]
- [[Discrete calculus]]
- [[Dormand–Prince method]]
- [[Exponential integrator]]
- [[Fast multipole method]]
- [[Finite difference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Adaptive_step_size