---
title: "Interest Flooding Attack"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Interest_Flooding_Attack"
wikipedia_categories: ["Computer network security", "Computer network stubs", "Cyberwarfare", "Denial-of-service attacks", "Internet stubs"]
related: ["[[DDoS mitigation]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[Firewall pinhole]]", "[[FTP bounce attack]]", "[[Miredo]]", "[[National Cyber Range Complex]]"]
---

# Interest Flooding Attack

An Interest Flooding Attack (IFA) is a denial-of-service attack in an Information-centric network (or Content-Centric Networking (CCN) or Named Data Networking (NDN)). An attacker requests existing or non-existing content in order to overload the distribution infrastructure. This can be implemented by sending Interest packets, which are not resolved at all or not resolved fast enough, and thus lead to malicious CPU or memory consumption.
This attack was previously denoted an open problem in ICN, only heuristic countermeasures available.  In 2016, Aubrey Alston and Tamer Refaei of The MITRE Corporation presented an exact solution to this problem which utilizes an in-packet cryptographic mechanism to remove the ability of high-volume Interest traffic to overload the distribution infrastructure of the network.

## Related

- [[DDoS mitigation]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Egress filtering]]
- [[Firewall pinhole]]
- [[FTP bounce attack]]
- [[Miredo]]
- [[National Cyber Range Complex]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interest_Flooding_Attack