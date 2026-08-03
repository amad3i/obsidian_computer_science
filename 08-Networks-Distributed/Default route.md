---
title: "Default route"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Default_route"
wikipedia_categories: ["Internet architecture", "Routing"]
related: ["[[AiScaler]]", "[[Any-source multicast]]", "[[AS 7007 incident]]", "[[Classless Inter-Domain Routing]]", "[[Echo (communications protocol)]]", "[[Hot-potato routing]]", "[[IEEE 802.1aq]]", "[[Internet Protocol Options]]", "[[Internet Routing Registry]]", "[[Multihoming]]"]
---

# Default route

In computer networking, the default route is a configuration of the Internet Protocol (IP) that establishes a forwarding rule for packets when no specific address of a next-hop host is available from the routing table or other routing mechanisms.
The default route is generally the address of another router, which treats the packet the same way: if a route matches, the packet is forwarded accordingly, otherwise the packet is forwarded to the default route of that router. The route evaluation process in each router uses the longest prefix match method to obtain the most specific route. The network with the longest subnet mask or network prefix that matches the destination IP address is the next-hop network gateway. The process repeats until a packet is delivered to the destination host, or earlier along the route, when a router has no default route available and cannot route the packet otherwise. In the latter case, the packet is dropped and an ICMP Destination Unreachable message may be returned. Each router traversal counts as one hop in the distance calculation for the transmission path.
The device to which the default route points is often called the default gateway, and it often carries out other functions such as packet filtering, firewalling, or proxy server operations.
The default route in Internet Protocol Version 4 (IPv4) is designated as the zero address, 0.0.0.0/0 in CIDR notation. Similarly, in IPv6, the default route is specified by ::/0. The subnet mask is specified as /0, which effectively specifies all networks and is the shortest match possible. A route lookup that does not match any other rule falls back to this route.
In the highest-level segment of a network, administrators generally point the default route for a given host towards the router that has a connection to a network service provider. Therefore, packets with destinations outside the organization's LAN, typically destinations on the Internet or a wide area network, are forwarded to the router with the connection to that provider.

## Related

- [[AiScaler]]
- [[Any-source multicast]]
- [[AS 7007 incident]]
- [[Classless Inter-Domain Routing]]
- [[Echo (communications protocol)]]
- [[Hot-potato routing]]
- [[IEEE 802.1aq]]
- [[Internet Protocol Options]]
- [[Internet Routing Registry]]
- [[Multihoming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Default_route