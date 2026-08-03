---
title: "Order One Network Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Order_One_Network_Protocol"
wikipedia_categories: ["Ad hoc routing protocols", "Wireless networking"]
related: ["[[Ad hoc wireless distribution service]]", "[[Augmented tree-based routing]]", "[[EraMobile]]", "[[ExOR]]", "[[Hazy Sighted Link State Routing Protocol]]", "[[List of ad hoc routing protocols]]", "[[ODMRP]]", "[[Optimized Link State Routing Protocol]]", "[[Temporally ordered routing algorithm]]", "[[Topology dissemination based on reverse-path forwarding]]"]
---

# Order One Network Protocol

The OrderOne MANET Routing Protocol is an algorithm for computers communicating by digital radio in a mesh network to find each other, and send messages to each other along a reasonably efficient path. It was designed for, and promoted as working with wireless mesh networks.
OON's designers say it can handle thousands of nodes, where most other protocols handle less than a hundred. OON uses hierarchical algorithms to minimize the total amount of transmissions needed for routing. Routing overhead is limited to between 1% and 5% of node-to-node bandwidth in any network and does not grow as the network size grows.
The basic idea is that a network organizes itself into a tree. Nodes meet at the root of the tree to establish an initial route. The route then moves away from the root by cutting corners, as ant-trails do. When there are no more corners to cut, a nearly optimum route exists. This route is continuously maintained. 
Each process can be performed with localized minimal communication, and very small router tables. OORP requires about 200K of memory. A simulated network with 500 nodes transmitting at 200 bytes/second organized itself in about 20 seconds.
As of 2004, OORP was patented or had other significant intellectual property restrictions. See the link below.

## Related

- [[Ad hoc wireless distribution service]]
- [[Augmented tree-based routing]]
- [[EraMobile]]
- [[ExOR]]
- [[Hazy Sighted Link State Routing Protocol]]
- [[List of ad hoc routing protocols]]
- [[ODMRP]]
- [[Optimized Link State Routing Protocol]]
- [[Temporally ordered routing algorithm]]
- [[Topology dissemination based on reverse-path forwarding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Order_One_Network_Protocol