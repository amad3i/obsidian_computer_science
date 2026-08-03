---
title: "VLAN"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/VLAN"
wikipedia_categories: ["Local area networks", "Network protocols"]
related: ["[[Local Area Transport]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Andrea Goldsmith (engineer)]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]"]
---

# VLAN

A virtual local area network (VLAN) is a local area network broadcast domain that is partitioned and isolated in a virtual network at the data link layer (OSI layer 2). A VLAN behaves like a virtual network switch or network link that can share the same physical structure with other VLANs while staying logically separate from them. 
VLANs work by applying tags to network frames that are forwarded within the broadcast domain, creating the appearance and functionality of network traffic that behaves as if it were split between separate networks. In this way, VLANs can keep network applications separate despite being connected to the same physical network, and without requiring multiple sets of cabling and networking devices to be deployed.
VLANs allow network administrators to group hosts together even if the hosts are not directly connected to the same network switch. Because VLAN membership can be configured through software, this can greatly simplify network design and deployment. Without VLANs, grouping hosts according to their resources requires relocating nodes or rewiring data links. VLANs allow devices that must be kept separate to share the cabling of a physical network and yet be prevented from directly interacting with one another. This managed sharing yields gains in simplicity, security, traffic control, and economy. 
Many Internet hosting services use VLANs to separate customers' private zones from one another, enabling each customer's servers to be grouped within a single network segment regardless of where the individual servers are located in the data center. Some precautions are needed to prevent traffic "escaping" from a given VLAN, an exploit known as VLAN hopping.
To subdivide a network into VLANs, one configures network equipment. Simpler equipment might partition only each physical port, in which case each VLAN runs over a dedicated network cable. More sophisticated devices can mark frames through VLAN tagging, so that a single interconnect (trunk) may be used to transport data for multiple VLANs. Since VLANs share bandwidth, a VLAN trunk can use link aggregation, quality-of-service prioritization, or both to route data efficiently.

## Related

- [[Local Area Transport]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Andrea Goldsmith (engineer)]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/VLAN