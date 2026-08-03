---
title: "Partial least squares regression"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Partial_least_squares_regression"
wikipedia_categories: ["Latent variable models", "Least squares"]
related: ["[[Common-method variance]]", "[[Doubly stochastic model]]", "[[Dynamic topic model]]", "[[Dynamic unobserved effects model]]", "[[Factor analysis]]", "[[Factor regression model]]", "[[First-difference estimator]]", "[[Item response theory]]", "[[Latent class model]]", "[[Latent Dirichlet allocation]]"]
---

# Partial least squares regression

Partial least squares (PLS) regression is a statistical method that bears some relation to principal components regression and is a reduced rank regression; instead of finding hyperplanes of maximum variance between the response and independent variables, it finds a linear regression model by projecting the predicted variables and the observable variables to a new space of maximum covariance (see below). Because both the X and Y data are projected to new spaces, the PLS family of methods are known as bilinear factor models. Partial least squares discriminant analysis (PLS-DA) is a variant used when the Y is categorical.
PLS is used to find the fundamental relations between two matrices (X and Y), i.e. a latent variable approach to modeling the covariance structures in these two spaces. A PLS model will try to find the multidimensional direction in the X space that explains the maximum multidimensional variance direction in the Y space. PLS regression is particularly suited when the matrix of predictors has more variables than observations, and when there is multicollinearity among X values. By contrast, standard regression will fail in these cases (unless it is regularized).
Partial least squares was introduced by the Swedish statistician Herman O. A. Wold, who then developed it with his son, Svante Wold. An alternative term for PLS is projection to latent structures, but the term partial least squares is still dominant in many areas. Although the original applications were in the social sciences, PLS regression is today most widely used in chemometrics and related areas. It is also used in bioinformatics, sensometrics, neuroscience, and anthropology.

## Related

- [[Common-method variance]]
- [[Doubly stochastic model]]
- [[Dynamic topic model]]
- [[Dynamic unobserved effects model]]
- [[Factor analysis]]
- [[Factor regression model]]
- [[First-difference estimator]]
- [[Item response theory]]
- [[Latent class model]]
- [[Latent Dirichlet allocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partial_least_squares_regression