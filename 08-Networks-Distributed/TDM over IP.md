---
title: "TDM over IP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/TDM_over_IP"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# TDM over IP

In computer networking and telecommunications, TDM over IP (TDMoIP) is the emulation of time-division multiplexing (TDM) over a packet-switched network (PSN). TDM refers to a T1, E1, T3 or E3 signal, while the PSN is based either on IP or MPLS or on raw Ethernet. A related technology is circuit emulation, which enables transport of TDM traffic over cell-based (ATM) networks.
TDMoIP is a type of pseudowire (PW). However, unlike other traffic types that can be carried over pseudowires (e.g. ATM, Frame Relay and Ethernet), TDM is a real-time bit stream, leading to TDMoIP having unique characteristics. In addition, conventional TDM networks have numerous special features, in particular those required in order to carry voice-grade telephony channels. These features imply signaling systems that support a wide range of telephony features, a rich standardization literature and well-developed Operations and Management (OAM) mechanisms. All of these factors must be taken into account when emulating TDM over PSNs.
One critical issue in implementing TDM PWs is clock recovery. In native TDM networks the physical layer carries highly accurate timing information along with the TDM data, but when emulating TDM over PSNs this synchronization is absent. TDM timing standards can be exacting and conformance with these may require innovative mechanisms to adaptively reproduce the TDM timing.
Another issue that must be addressed is TDMoIP packet loss concealment (PLC). Since TDM data is delivered at a constant rate over a dedicated channel, the native service may have bit errors but data is never lost in transit. All PSNs suffer to some degree from packet loss and this must be compensated when delivering TDM over a PSN.
In December 2007 TDMoIP was approved as an IETF RFC 5087 authored by Dr. Yaakov Stein, Ronen Shashua, Ron Insler, and Motti Anavi of RAD Data Communications.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TDM_over_IP