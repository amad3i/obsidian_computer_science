---
title: "Routing Information Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Routing_Information_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Routing protocols"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[IS-IS]]", "[[Open Shortest Path First]]", "[[Route poisoning]]", "[[Split horizon route advertisement]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]"]
---

# Routing Information Protocol

The Routing Information Protocol (RIP) is one of the oldest distance-vector routing protocols which employs the hop count as a routing metric. RIP prevents routing loops by implementing a limit on the number of hops allowed in a path from source to destination. The largest number of hops allowed for RIP is 15, which limits the size of networks that RIP can support.
RIP implements the split horizon, route poisoning, and holddown mechanisms to prevent incorrect routing information from being propagated.
In RIPv1 routers broadcast updates with their routing table every 30 seconds. In the early deployments, routing tables were small enough that the traffic was not significant. As networks grew in size, however, it became evident there could be a massive traffic burst every 30 seconds, even if the routers had been initialized at random times.
In most networking environments, RIP is not the preferred choice of routing protocol, as its time to converge and scalability are poor compared to EIGRP, OSPF, or IS-IS. However, it is easy to configure, because RIP does not require any parameters, unlike other protocols.
RIP uses the User Datagram Protocol (UDP) as its transport protocol, and is assigned the reserved port number 520.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[IS-IS]]
- [[Open Shortest Path First]]
- [[Route poisoning]]
- [[Split horizon route advertisement]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Routing_Information_Protocol