---
title: "Virtual Router Redundancy Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Virtual_Router_Redundancy_Protocol"
wikipedia_categories: ["First-hop redundancy protocols", "Internet protocols", "Routing protocols"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Constrained Shortest Path First]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[First-hop redundancy protocol]]", "[[IS-IS]]", "[[Multicast Source Discovery Protocol]]", "[[Open Shortest Path First]]", "[[Route poisoning]]"]
---

# Virtual Router Redundancy Protocol

The Virtual Router Redundancy Protocol (VRRP) is a network redundancy protocol standardized by the Internet Engineering Task Force (IETF). It provides high availability for the default gateway of an IP subnet by grouping multiple physical routers into a single virtual router that shares a common virtual IP address. The protocol is defined in the RFC 9568.
Within a VRRP group, one router is elected to act as the Active router, while one or more additional routers remain in the Backup state. Hosts on the network use the virtual IP address as their default gateway. If the Active router becomes unavailable, one of the Backup routers is automatically elected to assume the role, allowing gateway services to continue without requiring any reconfiguration of the hosts.
Each VRRP instance is limited, to a single IPv4 subnet or IPv6 link and cannot provide gateway redundancy across multiple Layer 3 networks. The protocol supports both IPv4 and IPv6 and can operate over various Layer 2 technologies, including Ethernet, MPLS and Token Ring.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Constrained Shortest Path First]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[First-hop redundancy protocol]]
- [[IS-IS]]
- [[Multicast Source Discovery Protocol]]
- [[Open Shortest Path First]]
- [[Route poisoning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Virtual_Router_Redundancy_Protocol