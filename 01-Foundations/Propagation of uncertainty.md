---
title: "Propagation of uncertainty"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Propagation_of_uncertainty"
wikipedia_categories: ["Algebra of random variables", "Numerical analysis", "Statistical approximations", "Statistical deviation and dispersion"]
related: ["[[Interval propagation]]", "[[Monte Carlo method]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]"]
---

# Propagation of uncertainty

In statistics, propagation of uncertainty is the effect of variables' uncertainties on the uncertainty of a function based on them. When the variables are the values of experimental measurements they have uncertainties due to measurement limitations (e.g., instrument precision) which propagate due to the combination of variables in the function.
The uncertainty u can be expressed in a number of ways.
It may be defined by the absolute error Δx. Uncertainties can also be defined by the relative error (Δx)/x, which is usually written as a percentage.
Most commonly, the uncertainty on a quantity is quantified in terms of the standard deviation, σ, which is the positive square root of the variance. The value of a quantity and its error are then expressed as an interval x ± u. 
However, the most general way of characterizing uncertainty is by specifying its probability distribution.
If the probability distribution of the variable is known or can be assumed, in theory it is possible to get any of its statistics. In particular, it is possible to derive confidence limits to describe the region within which the true value of the variable may be found. For example, the 68% confidence limits for a one-dimensional variable belonging to a normal distribution are approximately ± one standard deviation σ from the central value x, which means that the region x ± σ will cover the true value in roughly 68% of cases.
If the uncertainties are correlated then covariance must be taken into account. Correlation can arise from two different sources. First, the measurement errors may be correlated. Second, when the underlying values are correlated across a population, the uncertainties in the group averages will be correlated.
In a general context where a nonlinear function modifies the uncertain parameters (correlated or not), the standard tools to propagate uncertainty, and infer resulting quantity probability distribution/statistics, are sampling techniques from the Monte Carlo method family. For very large datasets or complex functions, the calculation of the error propagation may be very expensive so that a surrogate model or a parallel computing strategy may be necessary.
In some particular cases, the uncertainty propagation calculation can be done through simplistic algebraic procedures. Some of these scenarios are described below.

## Related

- [[Interval propagation]]
- [[Monte Carlo method]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Propagation_of_uncertainty