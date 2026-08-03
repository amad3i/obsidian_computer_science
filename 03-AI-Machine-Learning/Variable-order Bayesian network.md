---
title: "Variable-order Bayesian network"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Variable-order_Bayesian_network"
wikipedia_categories: ["Bayesian networks", "Markov models"]
related: ["[[Baum–Welch algorithm]]", "[[Bayesian hierarchical modeling]]", "[[Bernoulli scheme]]", "[[Burst error]]", "[[Causal Markov condition]]", "[[CLAWS (linguistics)]]", "[[Dependability state model]]", "[[Detailed balance]]", "[[Diffusion model]]", "[[Discrete phase-type distribution]]"]
---

# Variable-order Bayesian network

Variable-order Bayesian network (VOBN) models provide an important extension of both the Bayesian network models and the variable-order Markov models. VOBN models are used in machine learning in general and have shown great potential in bioinformatics applications.
These models extend the widely used position weight matrix (PWM) models, Markov models, and Bayesian network (BN) models.
In contrast to the BN models, where each random variable depends on a fixed subset of random variables, in VOBN models these subsets may vary based on the specific realization of observed variables. The observed realizations are often called the context and, hence, VOBN models are also known as context-specific Bayesian networks.
The flexibility in the definition of conditioning subsets of variables turns out to be a real advantage in classification and analysis applications, as the statistical dependencies between random variables in a sequence of variables (not necessarily adjacent) may be taken into account efficiently, and in a position-specific and context-specific manner.

## Related

- [[Baum–Welch algorithm]]
- [[Bayesian hierarchical modeling]]
- [[Bernoulli scheme]]
- [[Burst error]]
- [[Causal Markov condition]]
- [[CLAWS (linguistics)]]
- [[Dependability state model]]
- [[Detailed balance]]
- [[Diffusion model]]
- [[Discrete phase-type distribution]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Variable-order_Bayesian_network