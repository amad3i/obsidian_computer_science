---
title: "Projection filters"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Projection_filters"
wikipedia_categories: ["Computational statistics", "Control theory", "Nonlinear filters", "Signal estimation", "Stochastic differential equations"]
related: ["[[Kalman filter]]", "[[Switching Kalman filter]]", "[[Bellman filter]]", "[[Covariance intersection]]", "[[Filtering problem (stochastic processes)]]", "[[Moving horizon estimation]]", "[[Particle filter]]", "[[Unscented transform]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]"]
---

# Projection filters

Projection filters are a set of algorithms based on stochastic analysis and information geometry, or the differential geometric approach to statistics, used to find approximate solutions for filtering problems for nonlinear state-space systems.
The filtering problem consists of estimating the unobserved signal of a random dynamical system from partial noisy observations of the signal. The objective is computing the probability distribution of the signal conditional on the history of the noise-perturbed observations. This distribution allows for calculations of all statistics of the signal given the history of observations. If this distribution has a density, the density satisfies  specific stochastic partial differential equations (SPDEs) called Kushner-Stratonovich equation, or Zakai equation. 
It is known that the nonlinear filter density evolves in an infinite dimensional function space.
One can choose a finite dimensional family of probability densities, for example Gaussian densities, Gaussian mixtures, or exponential families, on which the infinite-dimensional filter density can be approximated. The basic idea of the projection filter is to use a geometric structure in the chosen spaces of densities to project the infinite dimensional SPDE of the optimal filter onto the chosen finite dimensional family, obtaining a finite dimensional stochastic differential equation (SDE) for the parameter of the density in the finite dimensional family that approximates the full filter evolution. To do this, the chosen finite dimensional family is equipped with a manifold structure as in information geometry. 
The projection filter was tested against the optimal filter for the cubic sensor problem. The projection filter could track effectively bimodal densities of the optimal filter that would have been difficult to approximate with standard algorithms like the extended Kalman filter.
Projection filters are ideal for in-line estimation, as they are quick to implement and run efficiently in time, providing a finite dimensional SDE for the parameter that can be implemented efficiently. 
Projection filters are also flexible, as they allow fine tuning the precision of the approximation by choosing richer approximating families, and some exponential families make the correction step in the projection filtering algorithm exact. Some formulations coincide with heuristic based  assumed density filters or with Galerkin methods. Projection filters can also approximate the full infinite-dimensional filter in an optimal way, beyond the optimal approximation of the SPDE coefficients alone, according to precise criteria such as mean square minimization. Projection filters have been studied by the Swedish Defense Research Agency  and have also been successfully applied to a variety of fields including navigation, ocean dynamics, quantum optics and quantum systems, estimation of fiber diameters, estimation of chaotic time series, change point detection and other areas.

## Related

- [[Kalman filter]]
- [[Switching Kalman filter]]
- [[Bellman filter]]
- [[Covariance intersection]]
- [[Filtering problem (stochastic processes)]]
- [[Moving horizon estimation]]
- [[Particle filter]]
- [[Unscented transform]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Projection_filters