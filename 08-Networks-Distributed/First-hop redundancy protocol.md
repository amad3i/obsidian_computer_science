---
title: "First-hop redundancy protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/First-hop_redundancy_protocol"
wikipedia_categories: ["Computer network stubs", "First-hop redundancy protocols", "Internet protocols"]
related: ["[[BGP Monitoring Protocol]]", "[[Compiled Wireless Markup Language]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[Fast Local Internet Protocol]]", "[[Host Monitoring Protocol]]", "[[Identifier-Locator Network Protocol]]", "[[Light-weight Identity]]", "[[Metro Ring Protocol]]", "[[Multicast Source Discovery Protocol]]"]
---

# First-hop redundancy protocol

First hop redundancy protocols (FHRP) are a category of networking protocols designed to protect the default gateway used on a subnetwork by allowing two or more routers to provide backup for that address. In the event of failure of an active router, the backup router will take over the address, usually within a few seconds.  In practice, such protocols can also be used to protect other services operating on a single IP address, not just routers.
Examples of such protocols include (in approximate order of creation):

Hot Standby Router Protocol (HSRP) - Cisco's initial, proprietary standard developed in 1998
Virtual Router Redundancy Protocol (VRRP) - an open (albeit patent-encumbered) standard protocol based largely on Cisco's HSRP
Common Address Redundancy Protocol (CARP) - patent-free, unencumbered alternative to Cisco's HSRP and the IETF's VRRP, developed in October 2003
Extreme Standby Router Protocol (ESRP) - Extreme Networks' proprietary standard with fast failover and layer 2 protection
Gateway Load Balancing Protocol (GLBP) - a more recent proprietary standard from Cisco that permits load balancing as well as redundancy
Routed Split multi-link trunking (R-SMLT) - an Avaya redundancy protocol
NetScreen Redundancy Protocol (NSRP) - a Juniper Networks proprietary router redundancy protocol providing load balancing
Chassis Cluster Redundant Ethernet - a Juniper Networks proprietary Ethernet redundancy protocol, used on its SRX platform
Multi-active Gateway Protocol (MAGP) - a Mellanox proprietary protocol based on VRRP that allows active-active operation

## Related

- [[BGP Monitoring Protocol]]
- [[Compiled Wireless Markup Language]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[Fast Local Internet Protocol]]
- [[Host Monitoring Protocol]]
- [[Identifier-Locator Network Protocol]]
- [[Light-weight Identity]]
- [[Metro Ring Protocol]]
- [[Multicast Source Discovery Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/First-hop_redundancy_protocol