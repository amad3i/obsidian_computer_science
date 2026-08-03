---
title: "Firewall pinhole"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Firewall_pinhole"
wikipedia_categories: ["Computer network security", "Computer network stubs"]
related: ["[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[FTP bounce attack]]", "[[Interest Flooding Attack]]", "[[Miredo]]", "[[NetStumbler]]", "[[Network Based Application Recognition]]"]
---

# Firewall pinhole

In computer networking, a firewall pinhole is a port that is not protected by a firewall to allow a particular application to gain access to a service on a host in the network protected by the firewall.
Leaving ports open in firewall configurations exposes the protected system to potentially malicious abuse. A fully closed firewall prevents applications from accessing services on the other side of the firewall. For protection, the mechanism for opening a pinhole in the firewall should implement user validation and authorization.
For firewalls performing a network address translation (NAT) function, the mapping between the external IP address, port socket and the internal IP address, port socket is often called a pinhole.
Pinholes can be created manually or programmatically. They can be temporary, created dynamically for a specific duration such as for a dynamic connection, or permanent, such as for signaling functions.
Firewalls sometimes automatically close pinholes after a period of time (typically a few minutes) to minimize the security exposure. Applications that require a pinhole to be kept open often need to generate artificial traffic through the pinhole in order to cause the firewall to restart its timer.

## Related

- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Egress filtering]]
- [[FTP bounce attack]]
- [[Interest Flooding Attack]]
- [[Miredo]]
- [[NetStumbler]]
- [[Network Based Application Recognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Firewall_pinhole