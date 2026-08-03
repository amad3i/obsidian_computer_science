---
title: "Hierarchical state routing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Hierarchical_state_routing"
wikipedia_categories: ["Computer network stubs", "Routing algorithms"]
related: ["[[Augmented tree-based routing]]", "[[Credit-based fair queuing]]", "[[MENTOR routing algorithm]]", "[[ODMRP]]", "[[A- search algorithm]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Application-layer framing]]", "[[Arc routing]]", "[[Authentication server]]"]
---

# Hierarchical state routing

Hierarchical state routing (HSR), proposed in Scalable Routing Strategies for Ad Hoc Wireless Networks by Iwata et al. (1999), is a typical example of a hierarchical routing protocol.
HSR maintains a hierarchical topology, where elected clusterheads at the lowest level become members of the next higher level. On the higher level, superclusters are formed, and so on. Nodes which want to communicate to a node outside of their cluster ask their clusterhead to forward their packet to the next level, until a clusterhead of the other node is in the same cluster. The packet then travels down to the destination node.
Furthermore, HSR proposes to cluster nodes in a logical way instead of in a geological way: members of the same company or in the same battlegroup are clustered together, assuming they will communicate much within the logical cluster.
HSR does not specify how a cluster is to be formed.

## Related

- [[Augmented tree-based routing]]
- [[Credit-based fair queuing]]
- [[MENTOR routing algorithm]]
- [[ODMRP]]
- [[A- search algorithm]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Application-layer framing]]
- [[Arc routing]]
- [[Authentication server]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hierarchical_state_routing