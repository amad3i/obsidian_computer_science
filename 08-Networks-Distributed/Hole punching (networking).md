---
title: "Hole punching (networking)"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Hole_punching_(networking)"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Hole punching (networking)

Hole punching (or sometimes punch-through) is a technique in computer networking for establishing a direct connection between two parties in which one or both are behind firewalls or behind routers that use network address translation (NAT). To punch a hole, each client connects to an unrestricted third-party server that temporarily stores external and internal address and port information for each client. The server then relays each client's information to the other, and using that information each client tries to establish direct connection; as a result of the connections using valid port numbers, restrictive firewalls or routers accept and forward the incoming packets on each side.
Hole punching does not require any knowledge of the network topology to function. ICMP hole punching, UDP hole punching and TCP hole punching respectively use Internet Control Message Protocol, User Datagram Protocol and Transmission Control Protocol.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hole_punching_(networking)