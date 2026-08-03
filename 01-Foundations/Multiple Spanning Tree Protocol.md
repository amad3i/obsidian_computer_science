---
title: "Multiple Spanning Tree Protocol"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiple_Spanning_Tree_Protocol"
wikipedia_categories: ["Ethernet standards", "Fault-tolerant computer systems", "Link protocols", "Network protocols", "Network topology", "Spanning tree"]
related: ["[[Spanning Tree Protocol]]", "[[Virtual Link Trunking]]", "[[Resilient Ethernet Protocol]]", "[[Virtual Link Aggregation Control Protocol]]", "[[Bonjour Sleep Proxy]]", "[[Dynamic synchronous transfer mode]]", "[[Frame Relay]]", "[[G.hn]]", "[[IEEE 802.1aq]]", "[[Link Layer Topology Discovery]]"]
---

# Multiple Spanning Tree Protocol

The Multiple Spanning Tree Protocol (MSTP) and algorithm, provides both simple and full connectivity assigned to any given virtual LAN (VLAN) throughout a bridged local area network. MSTP uses bridge protocol data unit (BPDUs) to exchange information between spanning-tree compatible devices, to prevent loops in each Multiple Spanning Tree instance (MSTI) and in the Common and Internal Spanning Tree (CIST), by selecting active and blocked paths. This is done as well as in Spanning Tree Protocol (STP) without the need of manually enabling backup links and getting rid of switching loop danger.
MSTP allows frames assigned to different VLANs to follow separate paths,  each based on an independent MSTI, within MST regions composed of local area networks (LANs) and MST bridges.  These regions and the other bridges and LANs are connected into a single common spanning tree (CST).

## Related

- [[Spanning Tree Protocol]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Multiple_Spanning_Tree_Protocol