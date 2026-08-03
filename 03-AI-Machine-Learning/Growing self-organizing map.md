---
title: "Growing self-organizing map"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Growing_self-organizing_map"
wikipedia_categories: ["Artificial neural networks", "Machine learning algorithms"]
related: ["[[Backpropagation]]", "[[Dehaene–Changeux model]]", "[[Hyper basis function network]]", "[[Leabra]]", "[[Linde–Buzo–Gray algorithm]]", "[[LoRA (machine learning)]]", "[[Quickprop]]", "[[Rprop]]", "[[Self-organizing map]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]"]
---

# Growing self-organizing map

A growing self-organizing map (GSOM) is a growing variant of a self-organizing map (SOM). The GSOM was developed to address the issue of identifying a suitable map size in the SOM. It starts with a minimal number of nodes (usually 4) and grows new nodes on the boundary based on a heuristic. By using the value called Spread Factor (SF), the data analyst has the ability to control the growth of the GSOM.
All the starting nodes of the GSOM are boundary nodes, i.e. each node has the freedom to grow in its own direction at the beginning. (Fig. 1) New Nodes are grown from the boundary nodes. Once a node is selected for growing all its free neighboring positions will be grown new nodes. The figure shows the three possible node growth options for a rectangular GSOM.

## Related

- [[Backpropagation]]
- [[Dehaene–Changeux model]]
- [[Hyper basis function network]]
- [[Leabra]]
- [[Linde–Buzo–Gray algorithm]]
- [[LoRA (machine learning)]]
- [[Quickprop]]
- [[Rprop]]
- [[Self-organizing map]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Growing_self-organizing_map