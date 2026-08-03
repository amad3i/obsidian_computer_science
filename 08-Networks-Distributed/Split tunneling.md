---
title: "Split tunneling"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Split_tunneling"
wikipedia_categories: ["Computer network security", "Internet privacy", "Network architecture", "Virtual private networks"]
related: ["[[Mobile virtual private network]]", "[[Virtual private network]]", "[[Application Defined Network]]", "[[Cisco Systems VPN Client]]", "[[CSS fingerprinting]]", "[[Darknet]]", "[[Deep packet inspection]]", "[[Device fingerprint]]", "[[EncroChat]]", "[[Extranet]]"]
---

# Split tunneling

In computer networking, split tunneling allows a user to access distinct security domains at the same time, using the same or different network connections. This connection state is usually facilitated through the simultaneous use of a LAN network interface controller (NIC), radio NIC, Wireless LAN NIC, and virtual private network client software application. Split tunneling is most commonly configured via the use of a remote-access VPN client, which allows the user to simultaneously connect to a nearby wireless network, resources on an off-site corporate network, as well as websites over the internet. 
A split tunnel configured to only tunnel traffic destined to a specific set of destinations is called a split-include tunnel. When configured to accept all traffic except traffic destined to a specific set of destinations, it is called a split-exclude tunnel.
Not every VPN allows split tunneling. Advantages of split tunneling include alleviating bottlenecks, conserving bandwidth (as internet traffic does not have to pass through the VPN server), and enabling a user to not have to continually connect and disconnect when remotely accessing resources.. Disadvantages include potentially bypassing gateway-level security that might be in place within the company infrastructure.  Internet service providers often use split tunneling to that implement for DNS hijacking purposes.

## Related

- [[Mobile virtual private network]]
- [[Virtual private network]]
- [[Application Defined Network]]
- [[Cisco Systems VPN Client]]
- [[CSS fingerprinting]]
- [[Darknet]]
- [[Deep packet inspection]]
- [[Device fingerprint]]
- [[EncroChat]]
- [[Extranet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Split_tunneling