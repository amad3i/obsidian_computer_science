---
title: "Resilient Ethernet Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Resilient_Ethernet_Protocol"
wikipedia_categories: ["Ethernet standards", "Link protocols", "Network protocols"]
related: ["[[Multiple Spanning Tree Protocol]]", "[[Spanning Tree Protocol]]", "[[Virtual Link Trunking]]", "[[Bonjour Sleep Proxy]]", "[[Dynamic synchronous transfer mode]]", "[[Frame Relay]]", "[[G.hn]]", "[[IEEE 802.1aq]]", "[[Link Layer Topology Discovery]]", "[[LocalTalk]]"]
---

# Resilient Ethernet Protocol

Resilient Ethernet Protocol (REP) is a network protocol developed by Cisco Systems as an alternative to the Rapid Spanning Tree Protocol (STP). Designed to enhance network reliability, REP mitigates the formation of loops, expedites recovery from link failures, and optimizes convergence times. It achieves this by managing a collection of ports that form a REP segment, ensuring the absence of bridging loops within that segment and facilitating rapid response to any interruptions in connectivity.
A REP segment is essentially a sequence of interconnected ports that share a common segment identifier. Each segment is composed of regular segment ports and a pair of edge ports configured by the user.
Limitations are placed on the configuration:

A single switch is restricted to having at most two ports in the same segment
REP is supported only on Trunk ports.
REP was initially designed to operate with Fast Ethernet (FE 10/100) interfaces, where it boasts a rapid link down detection time of approximately 10 milliseconds (ms) and a network convergence time around 50 ms. However, the performance of REP varies when deployed over different media types. For Fiber Gigabit Ethernet (GE) ports, the link down detection time remains at an expedient 10 ms, similar to that of Fast Ethernet ports. Conversely, when REP is implemented on Gigabit Ethernet copper interfaces, the detection and recovery times for link losses are notably longer, ranging between 750 ms and 350 ms.

## Related

- [[Multiple Spanning Tree Protocol]]
- [[Spanning Tree Protocol]]
- [[Virtual Link Trunking]]
- [[Bonjour Sleep Proxy]]
- [[Dynamic synchronous transfer mode]]
- [[Frame Relay]]
- [[G.hn]]
- [[IEEE 802.1aq]]
- [[Link Layer Topology Discovery]]
- [[LocalTalk]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Resilient_Ethernet_Protocol