---
title: "Diffusing update algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Diffusing_update_algorithm"
wikipedia_categories: ["Routing algorithms", "Routing protocols", "SRI International software"]
related: ["[[Babel (protocol)]]", "[[Distance-vector routing protocol]]", "[[Geographic routing]]", "[[Link-state routing protocol]]", "[[Optimized Link State Routing Protocol]]", "[[Vehicular Reactive Routing protocol]]", "[[A- search algorithm]]", "[[Acknowledgement (data networks)]]", "[[Arc routing]]", "[[Augmented tree-based routing]]"]
---

# Diffusing update algorithm

The diffusing update algorithm (DUAL) is the algorithm used by Cisco's EIGRP routing protocol to ensure that a given route is recalculated globally whenever it might cause a routing loop. It was developed by J.J. Garcia-Luna-Aceves at SRI International. The full name of the algorithm is DUAL finite-state machine (DUAL FSM). EIGRP is responsible for the routing within an autonomous system, and DUAL responds to changes in the routing topology and dynamically adjusts the routing tables of the router automatically.
EIGRP uses a feasibility condition to ensure that only loop-free routes are ever selected. The feasibility condition is conservative: when the condition is true, no loops can occur, but the condition might under some circumstances reject all routes to a destination although some are loop-free.
When no feasible route to a destination is available, the DUAL algorithm  invokes a diffusing computation  to ensure that all traces of the problematic route are eliminated from the network.  At which point the normal Bellman–Ford algorithm is used to recover a new route.

## Related

- [[Babel (protocol)]]
- [[Distance-vector routing protocol]]
- [[Geographic routing]]
- [[Link-state routing protocol]]
- [[Optimized Link State Routing Protocol]]
- [[Vehicular Reactive Routing protocol]]
- [[A- search algorithm]]
- [[Acknowledgement (data networks)]]
- [[Arc routing]]
- [[Augmented tree-based routing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Diffusing_update_algorithm