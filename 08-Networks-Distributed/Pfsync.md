---
title: "Pfsync"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Pfsync"
wikipedia_categories: ["BSD software", "Computer network stubs", "Firewall software", "FreeBSD", "High-availability cluster computing", "Internet protocols", "NetBSD", "Network software stubs"]
related: ["[[ALTQ]]", "[[Busdma]]", "[[Kqueue]]", "[[BGP Monitoring Protocol]]", "[[Compiled Wireless Markup Language]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[Fast Local Internet Protocol]]", "[[First-hop redundancy protocol]]", "[[Host Monitoring Protocol]]"]
---

# Pfsync

pfsync is a computer protocol used to synchronise firewall states between machines running Packet Filter (PF) for high availability. It is used along with CARP to make sure a backup firewall has the same information as the main firewall. When the main machine in the firewall cluster dies, the backup machine is able to accept current connections without loss.

## Related

- [[ALTQ]]
- [[Busdma]]
- [[Kqueue]]
- [[BGP Monitoring Protocol]]
- [[Compiled Wireless Markup Language]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[Fast Local Internet Protocol]]
- [[First-hop redundancy protocol]]
- [[Host Monitoring Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pfsync