---
title: "Egress filtering"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Egress_filtering"
wikipedia_categories: ["Computer network security", "Computer network stubs"]
related: ["[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Firewall pinhole]]", "[[FTP bounce attack]]", "[[Interest Flooding Attack]]", "[[Miredo]]", "[[NetStumbler]]", "[[Network Based Application Recognition]]"]
---

# Egress filtering

In computer networking, egress filtering is the practice of monitoring and potentially restricting the flow of information outbound from one network to another. Typically, it is information from a private TCP/IP computer network to the Internet that is controlled.
TCP/IP packets that are being sent out of the internal network are examined via a router, firewall, or similar edge device. Packets that do not meet security policies are not allowed to leave – they are denied "egress".
Egress filtering helps ensure that unauthorized or malicious traffic never leaves the internal network.
In a corporate network, typical recommendations are that all traffic except that emerging from a select set of servers would be denied egress. Restrictions can further be made such that only select protocols such as HTTP, email, and DNS are allowed. User workstations would then need to be configured either manually or via proxy auto-config to use one of the allowed servers as a proxy.
Corporate networks also typically have a limited number of internal address blocks in use. An edge device at the boundary between the internal corporate network and external networks (such as the Internet) is used to perform egress checks against packets leaving the internal network, verifying that the source IP address in all outbound packets is within the range of allocated internal address blocks.
Egress filtering may require policy changes and administrative work whenever a new application requires external network access. For this reason, egress filtering is an uncommon feature on consumer and very small business networks. PCI DSS requires outbound filtering to be in place on any server in the cardholder's environment. This is described in PCI-DSS v3.0, requirement 1.3.3.

## Related

- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Firewall pinhole]]
- [[FTP bounce attack]]
- [[Interest Flooding Attack]]
- [[Miredo]]
- [[NetStumbler]]
- [[Network Based Application Recognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Egress_filtering