---
title: "Realm-Specific IP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Realm-Specific_IP"
wikipedia_categories: ["Computer network stubs", "Internet protocols"]
related: ["[[BGP Monitoring Protocol]]", "[[Compiled Wireless Markup Language]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[Fast Local Internet Protocol]]", "[[First-hop redundancy protocol]]", "[[Host Monitoring Protocol]]", "[[Identifier-Locator Network Protocol]]", "[[Light-weight Identity]]", "[[Metro Ring Protocol]]"]
---

# Realm-Specific IP

Realm-Specific IP was an experimental IETF framework and protocol intended as an alternative to network address translation (NAT) in which the end-to-end integrity of packets is maintained.
RSIP lets a host borrow one or more IP addresses (and UDP/TCP port) from one or more RSIP gateways, by leasing (usually public) IP addresses and ports to RSIP hosts located in other (usually private) addressing realms.
The RSIP client requests registration with an RSIP gateway. The gateway in turn delivers either a unique IP address or a shared IP address and a unique set of TCP/UDP ports and associates the RSIP host address to this address. The RSIP host uses this address to send packets to destinations in the other realm. The tunnelled packets between RSIP host and gateway contain both addresses, and the RSIP gateway strips off the host address header and sends the packet to the destination. 
RSIP can also be used to relay traffic between several different privately addressed networks by leasing several different addresses to reach different destination networks.
RSIP should be useful for NAT traversal as an IETF standard alternative to Universal Plug and Play (UPnP).
As of November 2004, the protocol was in the experimental stage and not yet in widespread use.

## Related

- [[BGP Monitoring Protocol]]
- [[Compiled Wireless Markup Language]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[Fast Local Internet Protocol]]
- [[First-hop redundancy protocol]]
- [[Host Monitoring Protocol]]
- [[Identifier-Locator Network Protocol]]
- [[Light-weight Identity]]
- [[Metro Ring Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Realm-Specific_IP