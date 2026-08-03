---
title: "PFCP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/PFCP"
wikipedia_categories: ["3GPP standards", "5G (telecommunication)", "Internet Protocol", "LTE (telecommunication)", "Mobile technology", "Mobile telecommunications standards", "Network protocols", "Telecommunications infrastructure"]
related: ["[[GPRS Tunnelling Protocol]]", "[[RANAP]]", "[[Access stratum]]", "[[BSSGP]]", "[[CIMD]]", "[[Commercial Internet Protocol Security Option]]", "[[EMI (protocol)]]", "[[Non-access stratum]]", "[[Short Message Peer-to-Peer]]", "[[Source-specific multicast]]"]
---

# PFCP

Packet Forwarding Control Protocol (PFCP) is a 3GPP protocol used on the Sx/N4 interface between the control plane and the user plane function, specified in TS 29.244. It is one of the main protocols introduced in the 5G Next Generation Mobile Core Network (aka 5GC), but is also used in the 4G/LTE EPC to implement Control and User Plane Separation (CUPS). PFCP and the associated interfaces seek to formalize the interactions between different types of functional elements used in the Mobile Core Networks as deployed by most operators providing 4G, as well as 5G, services to mobile subscribers. These two types of components are:

The Control Plane (CP) functional elements, handling mostly signaling procedures (e.g. network attachment procedures, management of User-data Plane paths and even delivery of some light-weight services as SMS)
The User-data Plane (UP) functional elements, handling mostly packet forwarding, based on rules set by the CP elements (e.g. packet forwarding for IPv4, IPv6 - or possibly even Ethernet with future 5G deployments - between the various supported wireless RANs and the PDN representing the Internet or an enterprise network).
PFCP's scope is similar to that of OpenFlow, however it was engineered to serve the particular use-case of Mobile Core Networks.
PFCP is also used on the interface between the control plane and user plane functions of a disaggregated BNG, as defined by the BroadBand Forum in TR-459.

## Related

- [[GPRS Tunnelling Protocol]]
- [[RANAP]]
- [[Access stratum]]
- [[BSSGP]]
- [[CIMD]]
- [[Commercial Internet Protocol Security Option]]
- [[EMI (protocol)]]
- [[Non-access stratum]]
- [[Short Message Peer-to-Peer]]
- [[Source-specific multicast]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/PFCP