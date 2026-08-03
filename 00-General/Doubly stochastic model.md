---
title: "Doubly stochastic model"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Doubly_stochastic_model"
wikipedia_categories: ["Hidden stochastic models", "Latent variable models"]
related: ["[[Common-method variance]]", "[[Dynamic topic model]]", "[[Dynamic unobserved effects model]]", "[[Factor analysis]]", "[[Factor regression model]]", "[[First-difference estimator]]", "[[Item response theory]]", "[[Latent class model]]", "[[Latent Dirichlet allocation]]", "[[Latent semantic analysis]]"]
---

# Doubly stochastic model

In statistics, a doubly stochastic model is a type of model that can arise in many contexts, but in particular in modelling time-series and stochastic processes. 
The basic idea for a doubly stochastic model is that an observed random variable is modelled in two stages. In one stage, the distribution of the observed outcome is represented in a fairly standard way using one or more parameters. At a second stage, some of these parameters (often only one) are treated as being themselves random variables. In a univariate context this is essentially the same as the well-known concept of compounded distributions. For the more general case of doubly stochastic models, there is the idea that many values in a time-series or stochastic model are simultaneously affected by the underlying parameters, either by using a single parameter affecting many outcome variates, or by treating the underlying parameter as a time-series or stochastic process in its own right.
The basic idea here is essentially similar to that broadly used in latent variable models except that here the quantities playing the role of latent variables usually have an underlying dependence structure related to the time-series or spatial context.
An example of a doubly stochastic model is the following. The observed values in a point process might be modelled as a Poisson process in which the rate (the relevant underlying parameter) is treated as being the exponential of a Gaussian process.

## Related

- [[Common-method variance]]
- [[Dynamic topic model]]
- [[Dynamic unobserved effects model]]
- [[Factor analysis]]
- [[Factor regression model]]
- [[First-difference estimator]]
- [[Item response theory]]
- [[Latent class model]]
- [[Latent Dirichlet allocation]]
- [[Latent semantic analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Doubly_stochastic_model