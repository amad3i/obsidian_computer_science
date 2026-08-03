---
title: "Teredo tunneling"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Teredo_tunneling"
wikipedia_categories: ["IPv6 transition technologies", "Internet architecture", "Tunneling protocols"]
related: ["[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]", "[[Application-Layer Protocol Negotiation]]", "[[AS 7007 incident]]", "[[Authenticated Received Chain]]"]
---

# Teredo tunneling

In computer networking, Teredo is a Microsoft transition technology that gives full IPv6 connectivity for IPv6-capable hosts that are on the IPv4 Internet but have no native connection to an IPv6 network. Unlike similar protocols such as 6to4, it can perform its function even from behind network address translation (NAT) devices such as home routers.
Teredo operates using a platform independent tunneling protocol that provides IPv6 (Internet Protocol version 6) connectivity by encapsulating IPv6 datagram packets within IPv4 User Datagram Protocol (UDP) packets. Teredo routes these datagrams on the IPv4 Internet and through NAT devices. Teredo nodes elsewhere on the IPv6 network (called Teredo relays) receive the packets, un-encapsulate them, and pass them on.
Teredo is a temporary measure. In the long term, all IPv6 hosts should use native IPv6 connectivity. Teredo should be disabled when native IPv6 connectivity becomes available.  Christian Huitema developed Teredo at Microsoft, and the IETF standardized it as RFC 4380. The Teredo server listens on UDP port 3544.

## Related

- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[Anycast]]
- [[Application-layer framing]]
- [[Application-Layer Protocol Negotiation]]
- [[AS 7007 incident]]
- [[Authenticated Received Chain]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Teredo_tunneling