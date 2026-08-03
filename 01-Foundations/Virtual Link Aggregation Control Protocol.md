---
title: "Virtual Link Aggregation Control Protocol"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Virtual_Link_Aggregation_Control_Protocol"
wikipedia_categories: ["Avaya", "Computer network stubs", "Ethernet", "Link protocols", "Network protocols", "Network topology", "Nortel protocols"]
related: ["[[Ethernet over SDH]]", "[[Multiple Spanning Tree Protocol]]", "[[Provider Backbone Bridge Traffic Engineering]]", "[[Spanning Tree Protocol]]", "[[Virtual Link Trunking]]", "[[ATA over Ethernet]]", "[[Autonegotiation]]", "[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]"]
---

# Virtual Link Aggregation Control Protocol

Virtual LACP (VLACP) is an Avaya extension of the Link Aggregation Control Protocol to provide a Layer 2 handshaking protocol which can detect end-to-end failure between two physical Ethernet interfaces. It allows the switch to detect unidirectional or bi-directional link failures irrespective of intermediary devices and enables link recovery in less than one second.
With VLACP, far-end failures can be detected, which allows a Link aggregation trunk to fail over properly when end-to-end connectivity is not guaranteed for certain links through the internet in an aggregation group. When a remote link failure is detected, the change is propagated to the partner port.

## Related

- [[Ethernet over SDH]]
- [[Multiple Spanning Tree Protocol]]
- [[Provider Backbone Bridge Traffic Engineering]]
- [[Spanning Tree Protocol]]
- [[Virtual Link Trunking]]
- [[ATA over Ethernet]]
- [[Autonegotiation]]
- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Virtual_Link_Aggregation_Control_Protocol