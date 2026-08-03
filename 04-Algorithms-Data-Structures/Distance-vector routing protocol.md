---
title: "Distance-vector routing protocol"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Distance-vector_routing_protocol"
wikipedia_categories: ["Routing algorithms", "Routing protocols"]
related: ["[[Babel (protocol)]]", "[[Diffusing update algorithm]]", "[[Geographic routing]]", "[[Link-state routing protocol]]", "[[Optimized Link State Routing Protocol]]", "[[Vehicular Reactive Routing protocol]]", "[[A- search algorithm]]", "[[Acknowledgement (data networks)]]", "[[Arc routing]]", "[[Augmented tree-based routing]]"]
---

# Distance-vector routing protocol

A distance-vector routing protocol in data networks determines the best route for data packets based on distance. Distance-vector routing protocols measure the distance by the number of routers a packet has to pass; one router counts as one hop. Some distance-vector protocols also take into account network latency and other factors that influence traffic on a given route. To determine the best route across a network, routers using a distance-vector protocol exchange information with one another, usually routing tables plus hop counts for destination networks and possibly other traffic information. Distance-vector routing protocols also require that a router inform its neighbours of network topology changes periodically.
Distance-vector routing protocols use the Bellman–Ford algorithm to calculate the best route. Another way of calculating the best route across a network is based on link cost, and is implemented through link-state routing protocols.
The term distance vector refers to the fact that the protocol manipulates vectors (arrays) of distances to other nodes in the network.  The distance vector algorithm was the original ARPANET routing algorithm and was implemented more widely in local area networks with the Routing Information Protocol (RIP).

## Related

- [[Babel (protocol)]]
- [[Diffusing update algorithm]]
- [[Geographic routing]]
- [[Link-state routing protocol]]
- [[Optimized Link State Routing Protocol]]
- [[Vehicular Reactive Routing protocol]]
- [[A- search algorithm]]
- [[Acknowledgement (data networks)]]
- [[Arc routing]]
- [[Augmented tree-based routing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distance-vector_routing_protocol