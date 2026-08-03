---
title: "Label Distribution Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Label_Distribution_Protocol"
wikipedia_categories: ["MPLS networking", "Network protocols"]
related: ["[[Automatic switched-transport network]]", "[[Constrained Shortest Path First]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[MPLS-TP]]", "[[Router alert label]]", "[[T-MPLS]]", "[[Virtual leased line]]", "[[Virtual Private LAN Service]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]"]
---

# Label Distribution Protocol

Label Distribution Protocol (LDP) is a protocol in which routers capable of Multiprotocol Label Switching (MPLS) exchange label mapping information. Two routers with an established session are called LDP peers and the exchange of information is bi-directional.
LDP is used to build and maintain label-switched path (LSP) databases that are used to forward traffic through MPLS networks.
LDP can be used to distribute the inner label (VC/VPN/service label) and outer label (path label) in MPLS. For inner label distribution, targeted LDP (tLDP) is used.
LDP and tLDP discovery runs on UDP port 646 and the session is built on TCP port 646. During the discovery phase hello packets are sent on UDP port 646 to the 'all routers on this subnet' group multicast address (224.0.0.2). However, tLDP unicasts the hello packets to the targeted neighbor's address.

## Related

- [[Automatic switched-transport network]]
- [[Constrained Shortest Path First]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[MPLS-TP]]
- [[Router alert label]]
- [[T-MPLS]]
- [[Virtual leased line]]
- [[Virtual Private LAN Service]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Label_Distribution_Protocol