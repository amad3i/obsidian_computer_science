---
title: "Stochastic gradient descent"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stochastic_gradient_descent"
wikipedia_categories: ["Computational statistics", "Convex optimization", "Gradient methods", "M-estimators", "Machine learning algorithms", "Statistical approximations", "Stochastic optimization"]
related: ["[[Bootstrap aggregating]]", "[[FastICA]]", "[[Out-of-bag error]]", "[[Support vector machine]]", "[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithmic problems on convex sets]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Artificial precision]]"]
---

# Stochastic gradient descent

Stochastic gradient descent (often abbreviated SGD) is an iterative method for optimizing an objective function with suitable smoothness properties (e.g. differentiable or subdifferentiable). It can be regarded as a stochastic approximation of gradient descent optimization, since it replaces the actual gradient (calculated from the entire data set) by an estimate thereof (calculated from a randomly selected subset of the data). Especially in high-dimensional optimization problems this reduces the very high computational burden, achieving faster iterations in exchange for a lower convergence rate.
The basic idea behind stochastic approximation can be traced back to the Robbins–Monro algorithm of the 1950s. Today, stochastic gradient descent has become an important optimization method in machine learning.

## Related

- [[Bootstrap aggregating]]
- [[FastICA]]
- [[Out-of-bag error]]
- [[Support vector machine]]
- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithmic problems on convex sets]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Artificial precision]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stochastic_gradient_descent