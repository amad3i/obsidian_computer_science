---
title: "ZHLS-GF"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/ZHLS-GF"
wikipedia_categories: ["Ad hoc routing protocols", "Wireless networking"]
related: ["[[Ad hoc wireless distribution service]]", "[[Augmented tree-based routing]]", "[[EraMobile]]", "[[ExOR]]", "[[Hazy Sighted Link State Routing Protocol]]", "[[List of ad hoc routing protocols]]", "[[ODMRP]]", "[[Optimized Link State Routing Protocol]]", "[[Order One Network Protocol]]", "[[Temporally ordered routing algorithm]]"]
---

# ZHLS-GF

ZHLS-GF (Zone-Based Hierarchical Link State Routing Protocol with Gateway Flooding) is a hybrid routing protocol for computer networks that is based on ZHLS. 
In ZHLS, all network nodes construct two routing tables — an intra-zone routing table and an inter-zone routing table — by flooding NodeLSPs within the zone and ZoneLSPs throughout the network. However, this incurs a large communication overhead in the network. 
In ZHLS-GF, the flooding scheme floods ZoneLSPs only to the gateway nodes of zones, thus reducing the communication overhead significantly. Further, in ZHLS-GF only the gateway nodes store ZoneLSPs and constructs inter-zone routing tables, meaning that the total storage capacity required in the network is less than in ZHLS.

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

- Wikipedia: https://en.wikipedia.org/wiki/ZHLS-GF