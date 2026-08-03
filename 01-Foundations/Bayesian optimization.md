---
title: "Bayesian optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bayesian_optimization"
wikipedia_categories: ["Machine learning", "Sequential experiments", "Sequential methods", "Stochastic optimization"]
related: ["[[Multi-armed bandit]]", "[[Best arm identification]]", "[[Explore-then-commit algorithm]]", "[[Kullback–Leibler Upper Confidence Bound]]", "[[Lai–Robbins lower bound]]", "[[Reparameterization trick]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]"]
---

# Bayesian optimization

Bayesian optimization is a sequential model-based strategy for global optimization of black-box objective functions whose evaluations are costly. It is commonly used when a single observation requires an experiment, engineering computation, numerical simulation, or machine-learning run, and when derivatives are unavailable or unreliable. The objective need not have a closed-form expression.
The method constructs a probabilistic model of the unknown function, often a Gaussian process (GP), and uses the resulting predictive distribution to choose the next evaluation point. This choice is made by optimizing a sampling criterion, also called an acquisition function.
Common applications include hyperparameter optimization in machine learning, where each trial may require training and validating a model, and engineering design problems driven by expensive numerical simulations.

## Related

- [[Multi-armed bandit]]
- [[Best arm identification]]
- [[Explore-then-commit algorithm]]
- [[Kullback–Leibler Upper Confidence Bound]]
- [[Lai–Robbins lower bound]]
- [[Reparameterization trick]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bayesian_optimization