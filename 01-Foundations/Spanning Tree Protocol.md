---
title: "Spanning Tree Protocol"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Spanning_Tree_Protocol"
wikipedia_categories: ["Ethernet standards", "Fault-tolerant computer systems", "Link protocols", "Network protocols", "Network topology", "Spanning tree"]
related: ["[[Multiple Spanning Tree Protocol]]", "[[Virtual Link Trunking]]", "[[Resilient Ethernet Protocol]]", "[[Virtual Link Aggregation Control Protocol]]", "[[Bonjour Sleep Proxy]]", "[[Dynamic synchronous transfer mode]]", "[[Frame Relay]]", "[[G.hn]]", "[[IEEE 802.1aq]]", "[[Link Layer Topology Discovery]]"]
---

# Spanning Tree Protocol

The Spanning Tree Protocol (STP) is a network protocol that builds a loop-free logical topology for Ethernet networks. The basic function of STP is to prevent bridge loops and the broadcast radiation that results from them. Spanning tree also allows a network design to include backup links providing fault tolerance if an active link fails.
As the name suggests, STP creates a spanning tree that characterizes the relationship of nodes within a network of connected layer-2 bridges, and disables those links that are not part of the spanning tree, leaving a single active path between any two network nodes. STP is based on an algorithm that was invented by Radia Perlman while she was working for Digital Equipment Corporation.
In 2001, the IEEE introduced Rapid Spanning Tree Protocol (RSTP) as 802.1w. RSTP provides significantly faster recovery in response to network changes or failures, introducing new convergence behaviors and bridge port roles to do this. RSTP was designed to be backwards-compatible with standard STP.
STP was originally standardized as IEEE 802.1D but the functionality of spanning tree (802.1D), rapid spanning tree (802.1w), and Multiple Spanning Tree Protocol (802.1s) has since been incorporated into IEEE 802.1Q-2014.
While STP is still in use today, in many modern networks its primary use is as a loop-protection mechanism rather than a fault tolerance mechanism. Link aggregation protocols such as LACP bond multiple links to provide link-level fault tolerance while simultaneously increasing overall link capacity. However, implementing switch-level redundancy requires multi-chassis link aggregation, of which only proprietary variants exist. Shortest Path Bridging combines both loop-free forwarding and link aggregation, but hasn't reached STP's or LACP's popularity yet, as of 2026.

## Related

- [[Multiple Spanning Tree Protocol]]
- [[Virtual Link Trunking]]
- [[Resilient Ethernet Protocol]]
- [[Virtual Link Aggregation Control Protocol]]
- [[Bonjour Sleep Proxy]]
- [[Dynamic synchronous transfer mode]]
- [[Frame Relay]]
- [[G.hn]]
- [[IEEE 802.1aq]]
- [[Link Layer Topology Discovery]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spanning_Tree_Protocol