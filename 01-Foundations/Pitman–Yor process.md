---
title: "Pitman–Yor process"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Pitman–Yor_process"
wikipedia_categories: ["Cluster analysis algorithms", "Nonparametric Bayesian statistics", "Stochastic processes"]
related: ["[[Gaussian process]]", "[[Additive process]]", "[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]"]
---

# Pitman–Yor process

In probability theory,  a Pitman–Yor process denoted PY(d, θ, G0), is a stochastic process whose sample path is a probability distribution. A random sample from this process is an infinite discrete probability distribution, consisting of an infinite set of atoms drawn from G0, with weights drawn from a two-parameter Poisson-Dirichlet distribution.  The process is named after Jim Pitman and Marc Yor.
The parameters governing the Pitman–Yor process are: 0 ≤ d < 1 a discount parameter, a strength parameter θ > −d and a base distribution G0 over a probability space  X. When d = 0, it becomes the Dirichlet process.  The discount parameter gives the Pitman–Yor process more flexibility over tail behavior than the Dirichlet process, which has exponential tails.  This makes Pitman–Yor process useful for modeling data with power-law tails (e.g., word frequencies in natural language).
The exchangeable random partition induced by the Pitman–Yor process is an example of a Chinese restaurant process, a Poisson–Kingman partition, and of a Gibbs type random partition.
The Pitman-Yor process is used to model the observation process of words, or species, etc. It is useful because it can generate phenomena with heavy-tailed distributions.

## Related

- [[Gaussian process]]
- [[Additive process]]
- [[Automatic clustering algorithms]]
- [[BIRCH]]
- [[Canopy clustering algorithm]]
- [[Cluster-weighted modeling]]
- [[Cobweb (clustering)]]
- [[Constrained clustering]]
- [[Data stream clustering]]
- [[DBSCAN]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pitman–Yor_process