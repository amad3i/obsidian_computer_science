---
title: "Moral graph"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Moral_graph"
wikipedia_categories: ["Bayesian networks", "Graph operations", "Graphical models"]
related: ["[[Plate notation]]", "[[Bayesian hierarchical modeling]]", "[[Belief propagation]]", "[[Causal Markov condition]]", "[[Dependability state model]]", "[[Dynamic Bayesian network]]", "[[Factor graph]]", "[[Generalized distributive law]]", "[[Graphical model]]", "[[Graphical models for protein structure]]"]
---

# Moral graph

In graph theory, a moral graph is used to find the equivalent undirected form of a directed acyclic graph. It is a key step of the junction tree algorithm, used in belief propagation on graphical models.

The moralized counterpart of a directed acyclic graph is formed by adding edges between all pairs of non-adjacent nodes that have a common child, and then making all edges in the graph undirected. Equivalently, a moral graph of a directed acyclic graph G is an undirected graph in which each node of the original G is now connected to its Markov blanket. The name stems from the fact that, in a moral graph, two nodes that have a common child are required to be married by sharing an edge.
Moralization may also be applied to mixed graphs, called in this context "chain graphs". In a chain graph, a connected component of the undirected subgraph is called a chain. Moralization adds an undirected edge between any two vertices that both have outgoing edges to the same chain, and then forgets the orientation of the directed edges of the graph.

## Related

- [[Plate notation]]
- [[Bayesian hierarchical modeling]]
- [[Belief propagation]]
- [[Causal Markov condition]]
- [[Dependability state model]]
- [[Dynamic Bayesian network]]
- [[Factor graph]]
- [[Generalized distributive law]]
- [[Graphical model]]
- [[Graphical models for protein structure]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Moral_graph