---
title: "Causal Markov condition"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Causal_Markov_condition"
wikipedia_categories: ["Bayesian networks", "Causality"]
related: ["[[Bayesian hierarchical modeling]]", "[[Causal system]]", "[[Directed acyclic graph]]", "[[Dynamic Bayesian network]]", "[[Escalation archetype]]", "[[Influence diagram]]", "[[Junction tree algorithm]]", "[[Latent Dirichlet allocation]]", "[[Moral graph]]", "[[Neural network Gaussian process]]"]
---

# Causal Markov condition

The Causal Markov (CM) condition states that, conditional on the set of all its direct causes, a node is independent of all variables which are not effects or direct causes of that node. In the event that the structure of a Bayesian network accurately depicts causality, the two conditions are equivalent. 
This is related to the Markov condition, an assumption made in Bayesian probability theory, that every node in a Bayesian network is conditionally independent of its nondescendants, given its parents. Stated loosely, it is assumed that a node has no bearing on nodes which do not descend from it. In a DAG, this local Markov condition is equivalent to the global Markov condition, which states that d-separations in the graph also correspond to conditional independence relations. This also means that a node is conditionally independent of the entire network, given its Markov blanket. A network may accurately embody the Markov condition without depicting causality, in which case it should not be assumed to embody the causal Markov condition.

## Related

- [[Bayesian hierarchical modeling]]
- [[Causal system]]
- [[Directed acyclic graph]]
- [[Dynamic Bayesian network]]
- [[Escalation archetype]]
- [[Influence diagram]]
- [[Junction tree algorithm]]
- [[Latent Dirichlet allocation]]
- [[Moral graph]]
- [[Neural network Gaussian process]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Causal_Markov_condition