---
title: "Link-state routing protocol"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Link-state_routing_protocol"
wikipedia_categories: ["Routing algorithms", "Routing protocols"]
related: ["[[Babel (protocol)]]", "[[Diffusing update algorithm]]", "[[Distance-vector routing protocol]]", "[[Geographic routing]]", "[[Optimized Link State Routing Protocol]]", "[[Vehicular Reactive Routing protocol]]", "[[A- search algorithm]]", "[[Acknowledgement (data networks)]]", "[[Arc routing]]", "[[Augmented tree-based routing]]"]
---

# Link-state routing protocol

Link-state routing protocols are one of the two main classes of routing protocols used in packet switching networks for computer communications, the others being distance-vector routing protocols. Examples of link-state routing protocols include Open Shortest Path First (OSPF) and Intermediate System to Intermediate System (IS-IS).
The link-state protocol is performed by every switching node in the network (i.e., nodes which are prepared to forward packets; in the Internet, these are called routers). The basic concept of link-state routing is that every node constructs a map of the connectivity to the network in the form of a graph, showing which nodes are connected to which other nodes. Each node then independently calculates the next best logical path from it to every possible destination in the network. Each collection of best paths will then form each node's routing table.
This contrasts with distance-vector routing protocols, which work by having each node share its routing table with its neighbors. In a link-state protocol, the only information passed between nodes is connectivity related. Link-state algorithms are sometimes characterized informally as each router "telling the world about its neighbors."

## Related

- [[Babel (protocol)]]
- [[Diffusing update algorithm]]
- [[Distance-vector routing protocol]]
- [[Geographic routing]]
- [[Optimized Link State Routing Protocol]]
- [[Vehicular Reactive Routing protocol]]
- [[A- search algorithm]]
- [[Acknowledgement (data networks)]]
- [[Arc routing]]
- [[Augmented tree-based routing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Link-state_routing_protocol