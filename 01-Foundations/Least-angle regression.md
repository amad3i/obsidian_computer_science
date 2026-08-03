---
title: "Least-angle regression"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Least-angle_regression"
wikipedia_categories: ["Estimation theory", "Parametric statistics", "Regression variable selection", "Single-equation methods (econometrics)"]
related: ["[[Linear regression]]", "[[Multi-attribute global inference of quality]]", "[[Cross-validation (statistics)]]", "[[Data assimilation]]", "[[Estimation]]", "[[Estimation theory]]", "[[Fisher information]]", "[[Formation matrix]]", "[[Generalized pencil-of-function method]]", "[[Group method of data handling]]"]
---

# Least-angle regression

In statistics, least-angle regression (LARS) is an algorithm for fitting linear regression models to high-dimensional data, developed by Bradley Efron, Trevor Hastie, Iain Johnstone and Robert Tibshirani.
Suppose we expect a response variable to be determined by a linear combination of a subset of potential covariates.  Then the LARS algorithm provides a means of producing an estimate of which variables to include, as well as their coefficients.
Instead of giving a vector result, the LARS solution consists of a curve denoting the solution for each value of the L1 norm of the parameter vector. The algorithm is similar to forward stepwise regression, but instead of including variables at each step, the estimated parameters are increased in a direction equiangular to each one's correlations with the residual.

## Related

- [[Linear regression]]
- [[Multi-attribute global inference of quality]]
- [[Cross-validation (statistics)]]
- [[Data assimilation]]
- [[Estimation]]
- [[Estimation theory]]
- [[Fisher information]]
- [[Formation matrix]]
- [[Generalized pencil-of-function method]]
- [[Group method of data handling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Least-angle_regression