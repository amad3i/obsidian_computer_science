---
title: "Virtual Private LAN Service"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Virtual_Private_LAN_Service"
wikipedia_categories: ["MPLS networking", "Network protocols", "Virtual private networks"]
related: ["[[Automatic switched-transport network]]", "[[Constrained Shortest Path First]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Label Distribution Protocol]]", "[[MPLS-TP]]", "[[Router alert label]]", "[[T-MPLS]]", "[[Virtual leased line]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]"]
---

# Virtual Private LAN Service

Virtual Private LAN Service (VPLS) is a virtual private network (VPN) technology that provides Ethernet-based multipoint-to-multipoint communication over IP or MPLS networks. It allows geographically dispersed sites to share an Ethernet broadcast domain by connecting sites (including both servers and clients) through pseudowires. The technologies that can be used as pseudo-wire can be Ethernet over MPLS, L2TPv3 or even GRE. There are two IETF standards-track RFCs (RFC 4761 and RFC 4762) describing VPLS establishment. In contrast to L2TPv3, which allows only point-to-point OSI layer 2 tunnels, VPLS allows any-to-any (multipoint) connectivity.
Since VPLS emulates a LAN, full mesh connectivity is required. In a VPLS, the local area network (LAN) at each site is extended to the edge of the provider network. The provider network then emulates a switch or bridge to connect all of the customer LANs to create a single bridged LAN. There are two methods for full mesh establishment for VPLS: using Border Gateway Protocol (BGP) and using Label Distribution Protocol (LDP). BGP mechanisms used are very similar to those used in establishing OSI layer 3 MPLS VPNs and provide both auto-discovery and signalling; each provider edge (PE) router configured to participate in a given VPLS, through the use of BGP, simultaneously discovers all other PEs in the same VPLS, establishing a full mesh of pseudowires. With LDP, each PE router must be given the addresses of other PEs participating in the same VPLS. A full mesh of LDP sessions is then established, before LDP is used to create an equivalent mesh of pseudowires.
Benefits of VPLS include flexible bandwidth, sophisticated service level agreements, simplicity, and cost-effectiveness. VPLS users can also connect all of their sites to an Ethernet VPN that provides a secure, high speed and homogenous network.

## Related

- [[Automatic switched-transport network]]
- [[Constrained Shortest Path First]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Label Distribution Protocol]]
- [[MPLS-TP]]
- [[Router alert label]]
- [[T-MPLS]]
- [[Virtual leased line]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Virtual_Private_LAN_Service