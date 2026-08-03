---
title: "Hybrid Wireless Mesh Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Hybrid_Wireless_Mesh_Protocol"
wikipedia_categories: ["Computer network stubs", "IEEE 802.11", "Network protocols"]
related: ["[[AEGIS SecureConnect]]", "[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]", "[[Bearer-Independent Call Control]]", "[[Common Industrial Protocol]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Content Vectoring Protocol]]", "[[ControlNet]]", "[[Digital Data Communications Message Protocol]]"]
---

# Hybrid Wireless Mesh Protocol

The Hybrid Wireless Mesh Protocol (HWMP), part of IEEE 802.11s, is a basic routing protocol for a wireless mesh network.  It is based on Ad hoc On-Demand Distance Vector (AODV) Routing (RFC 3561) and tree-based routing.  It relies on a Peer Link Management protocol by which each Mesh Point discovers and tracks neighboring nodes.  If any of these are connected to a wired backhaul, there is no need for HWMP, which selects paths from those assembled by compiling all mesh point peers into one composite map.
The HWMP protocol is hybrid, because it consists of a proactive tree-based hierarchical routing protocol, and an on-demand logic, based on the AODV protocol. In contradiction with classic IP based (OSI layer 3, network) routing, the HWMP protocol is based on MAC addresses (layer 2, data link).
HWMP is intended to displace proprietary protocols used by vendors like Meraki for the same purpose, permitting peer participation by open source router firmware. The open source implementation of 802.11s (open80211s) has been integrated into the Linux kernel by Cozybit Inc.  FreeBSD supports HWMP starting with FreeBSD 8.0.

## Related

- [[AEGIS SecureConnect]]
- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]
- [[Bearer-Independent Call Control]]
- [[Common Industrial Protocol]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Content Vectoring Protocol]]
- [[ControlNet]]
- [[Digital Data Communications Message Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hybrid_Wireless_Mesh_Protocol