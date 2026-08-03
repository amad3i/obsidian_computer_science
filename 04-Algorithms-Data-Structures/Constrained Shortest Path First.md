---
title: "Constrained Shortest Path First"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Constrained_Shortest_Path_First"
wikipedia_categories: ["Internet protocols", "MPLS networking", "Network protocols", "Routing protocols"]
related: ["[[Acknowledgement (data networks)]]", "[[Automatic switched-transport network]]", "[[BEEP]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Domain Name System]]", "[[Exterior Gateway Protocol]]"]
---

# Constrained Shortest Path First

Constrained Shortest Path First (CSPF) is an extension of shortest path algorithms. The path computed using CSPF is a shortest path fulfilling a set of constraints. It simply means that it runs shortest path algorithm after pruning those links that violate a given set of constraints. A constraint could be minimum bandwidth required per link (also known as bandwidth guaranteed constraint), end-to-end delay, maximum number of links traversed, include/exclude nodes. CSPF is widely used in MPLS Traffic Engineering. The routing using CSPF is known as Constraint Based Routing (CBR).
The path computed using CSPF could be exactly same as that of computed from OSPF and IS-IS, or it could be completely different depending on the set of constraints to be met.

## Related

- [[Acknowledgement (data networks)]]
- [[Automatic switched-transport network]]
- [[BEEP]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Domain Name System]]
- [[Exterior Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constrained_Shortest_Path_First