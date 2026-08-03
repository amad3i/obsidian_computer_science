---
title: "Regularized least squares"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Regularized_least_squares"
wikipedia_categories: ["Inverse problems", "Least squares", "Linear algebra"]
related: ["[[Backus–Gilbert method]]", "[[Least-squares spectral analysis]]", "[[Ridge regression]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]"]
---

# Regularized least squares

Regularized least squares (RLS) is a family of methods for solving the least-squares problem while using regularization to further constrain the resulting solution.
RLS is used for two main reasons. The first comes up when the number of variables in the linear system exceeds the number of observations. In such settings, the ordinary least-squares problem is ill-posed and is therefore impossible to fit because the associated optimization problem has infinitely many solutions. RLS allows the introduction of further constraints that uniquely determine the solution.
The second reason for using RLS arises when the learned model suffers from poor generalization. RLS can be used in such cases to improve the generalizability of the model by constraining it at training time. This constraint can either force the solution to be "sparse" in some way or to reflect other prior knowledge about the problem such as information about correlations between features. A Bayesian understanding of this can be reached by showing that RLS methods are often equivalent to priors on the solution to the least-squares problem.

## Related

- [[Backus–Gilbert method]]
- [[Least-squares spectral analysis]]
- [[Ridge regression]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Regularized_least_squares