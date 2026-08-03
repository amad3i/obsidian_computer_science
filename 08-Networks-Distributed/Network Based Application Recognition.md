---
title: "Network Based Application Recognition"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Network_Based_Application_Recognition"
wikipedia_categories: ["Computer network security", "Computer network stubs"]
related: ["[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[Firewall pinhole]]", "[[FTP bounce attack]]", "[[Interest Flooding Attack]]", "[[Miredo]]", "[[NetStumbler]]"]
---

# Network Based Application Recognition

Network Based Application Recognition (NBAR) is the mechanism used by some Cisco routers and switches to recognize a dataflow by inspecting some packets sent.
The networking equipment which uses NBAR does a deep packet inspection on some of the packets in a dataflow, to determine which traffic category the flow belongs to. Used in conjunction with other features, it may then program the internal application-specific integrated circuits (ASICs) to handle this flow appropriately. The categorization may be done with Open Systems Interconnection (OSI) layer 4 info, packet content, signaling, and so on but some new applications have made it difficult on purpose to cling to this kind of tagging.
The NBAR approach is useful in dealing with malicious software using known ports to fake being "priority traffic", as well as non-standard applications using dynamic ports. That's why NBAR is also known as OSI layer 7 categorization.
On Cisco routers, NBAR is mainly used for quality of service and network security purposes.

## Related

- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Egress filtering]]
- [[Firewall pinhole]]
- [[FTP bounce attack]]
- [[Interest Flooding Attack]]
- [[Miredo]]
- [[NetStumbler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Network_Based_Application_Recognition