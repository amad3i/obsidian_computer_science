---
title: "Proxy ARP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Proxy_ARP"
wikipedia_categories: ["Internet Standards", "Internet protocols"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]"]
---

# Proxy ARP

Proxy ARP is a technique by which a proxy server on a given network answers the Address Resolution Protocol (ARP) queries for an IP address that is not on that network. The proxy is aware of the location of the traffic's destination and offers its own MAC address as the (ostensibly final) destination). The traffic directed to the proxy address is then typically routed by the proxy to the intended destination via another interface or via a tunnel.
The process, which results in the proxy server responding with its own MAC address to an ARP request for a different IP address for proxying purposes, is sometimes referred to as publishing.

## Related

- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]
- [[Directory information tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Proxy_ARP