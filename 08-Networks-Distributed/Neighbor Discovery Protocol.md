---
title: "Neighbor Discovery Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Neighbor_Discovery_Protocol"
wikipedia_categories: ["Computer-related introductions in 1996", "IPv6", "Internet Standards", "Internet protocols", "Link protocols"]
related: ["[[Multicast Listener Discovery]]", "[[Reverse Address Resolution Protocol]]", "[[Secure Neighbor Discovery]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]"]
---

# Neighbor Discovery Protocol

The Neighbor Discovery Protocol (NDP), or simply Neighbor Discovery (ND), is a protocol of the Internet protocol suite used with Internet Protocol Version 6 (IPv6).  It operates at the internet layer of the Internet model, and is responsible for gathering various information required for network communication, including the configuration of local connections and the domain name servers and gateways.
The protocol defines five ICMPv6 packet types to perform functions for IPv6 similar to the Address Resolution Protocol (ARP) and Internet Control Message Protocol (ICMP) Router Discovery and Router Redirect protocols for IPv4. It provides many improvements over its IPv4 counterparts. For example, it includes Neighbor Unreachability Detection (NUD), thus improving robustness of packet delivery in the presence of failing routers or links, or mobile nodes.
The Inverse Neighbor Discovery (IND) protocol extension allows nodes to determine and advertise an IPv6 address corresponding to a given link-layer address, similar to Inverse ARP for IPv4.
The Secure Neighbor Discovery Protocol (SEND), a security extension of NDP, uses Cryptographically Generated Addresses (CGA) and the Resource Public Key Infrastructure (RPKI) to provide an alternative mechanism for securing NDP with a cryptographic method that is independent of IPsec. Neighbor Discovery Proxy (ND Proxy) provides a service similar to IPv4 Proxy ARP and allows bridging multiple network segments within a single subnet prefix when bridging cannot be done at the link layer.

## Related

- [[Multicast Listener Discovery]]
- [[Reverse Address Resolution Protocol]]
- [[Secure Neighbor Discovery]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Neighbor_Discovery_Protocol