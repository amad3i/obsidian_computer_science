---
title: "Topology dissemination based on reverse-path forwarding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Topology_dissemination_based_on_reverse-path_forwarding"
wikipedia_categories: ["Ad hoc routing protocols", "SRI International", "Wireless networking"]
related: ["[[Ad hoc wireless distribution service]]", "[[Augmented tree-based routing]]", "[[EraMobile]]", "[[ExOR]]", "[[Hazy Sighted Link State Routing Protocol]]", "[[List of ad hoc routing protocols]]", "[[ODMRP]]", "[[Optimized Link State Routing Protocol]]", "[[Order One Network Protocol]]", "[[Temporally ordered routing algorithm]]"]
---

# Topology dissemination based on reverse-path forwarding

Topology broadcast based on reverse-path forwarding (TBRPF) is a link-state routing protocol for wireless mesh networks.
The obvious design for a wireless link-state protocol (such as the optimized link-state routing protocol) transmits large amounts of routing data, and this limits the utility of a link-state protocol when the network is made of moving nodes.  The number and size of the routing transmissions make the network unusable for any but the smallest networks.
The conventional solution is to use a distance-vector routing protocol such as AODV, which usually transmits no data about routing.  However, distance-vector routing requires more time to establish a connection, and the routes are less optimized than a link-state router.
TBRPF transmits only the differences between the previous network state and the current network state.  Therefore, routing messages are smaller, and can therefore be sent more frequently.  This means that nodes' routing tables are more up-to-date.
TBRPF is controlled under a US patent filed in December 2000 and assigned to SRI International (Patent ID 6845091, issued January 18, 2005).

## Related

- [[Ad hoc wireless distribution service]]
- [[Augmented tree-based routing]]
- [[EraMobile]]
- [[ExOR]]
- [[Hazy Sighted Link State Routing Protocol]]
- [[List of ad hoc routing protocols]]
- [[ODMRP]]
- [[Optimized Link State Routing Protocol]]
- [[Order One Network Protocol]]
- [[Temporally ordered routing algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Topology_dissemination_based_on_reverse-path_forwarding