---
title: "ICMP hole punching"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/ICMP_hole_punching"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# ICMP hole punching

ICMP hole punching is a technique employed in network address translator (NAT) applications for maintaining Internet Control Message Protocol (ICMP) packet streams that traverse the NAT. NAT traversal techniques are typically required for client-to-client networking applications on the Internet involving hosts connected in private networks, especially in peer-to-peer and Voice over Internet Protocol (VoIP) deployments.
ICMP hole punching establishes connectivity between two hosts communicating across one or more network address translators in either a peer-to-peer or client–server model. Typically, third party hosts on the public transit network are used to establish UDP or TCP port states that may be used for direct communications between the communicating hosts, however ICMP hole punching requires no third party involvement to pass information between one or more NATs by exploiting a NAT's loose acceptance of inbound ICMP Time Exceeded packets.
Once an ICMP Time Exceeded packet reaches the destination NAT, arbitrary data in the packet expected by the NAT allows the packet to reach the destination server, allowing the destination server to obtain the client's public IP address and other data stored in the packet from the client.

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

- Wikipedia: https://en.wikipedia.org/wiki/ICMP_hole_punching