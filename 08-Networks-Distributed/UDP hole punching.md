---
title: "UDP hole punching"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/UDP_hole_punching"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# UDP hole punching

UDP hole punching is a commonly used technique employed in network address translation (NAT) applications for maintaining User Datagram Protocol (UDP) packet streams that traverse the NAT. NAT traversal techniques are typically required for client-to-client networking applications on the Internet involving hosts connected in private networks, especially in peer-to-peer, Direct Client-to-Client (DCC) and Voice over Internet Protocol (VoIP) deployments.
UDP hole punching establishes connectivity between two hosts communicating across one or more network address translators. Typically, third-party hosts on the public transit network are used to establish UDP port states that may be used for direct communications between the communicating hosts. Once port state has been successfully established and the hosts are communicating, port state may be maintained either by normal communications traffic, or in the prolonged absence thereof, by keep-alive packets, usually consisting of empty UDP packets or packets with minimal, non-intrusive content.

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

- Wikipedia: https://en.wikipedia.org/wiki/UDP_hole_punching