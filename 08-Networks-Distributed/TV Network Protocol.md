---
title: "TV Network Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/TV_Network_Protocol"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# TV Network Protocol

The TV Network Protocol or TVNP as it is more commonly referred to is an open network protocol developed to enable CCTV systems from any manufacturer to be integrated into an existing CCTV network. It provides high levels of support for audio routing, video routing and camera control.
The protocol was developed by Philips Projects (now Tyco Integrated Systems) on behalf of the Traffic Control Systems Unit (TCSU), now a part of Transport for London (TfL). Tyco acts as the standards and approvals house for companies who want to implement the protocol.
The protocol's roots can be traced back to the Highways Agency HDLC standard. It is the property of TfL and is independent of any supplier. As of late of 2011 there are at least eight manufacturers who have a partial or full TVNP interface, including:

BAE Systems (previously Petards)
Chubb (previously Initial Fire and Security)
Honeywell
Infinitronix
Meyertech
Costain (previously Simulation Systems Limited)
Synectics
Tyco (previously Philips Projects).
TVNP layers are broadly based on the OSI model. TVNP Layer 2 and 3 correspond to OSI Layers 2 and 3. When used over RS-232 only, TVNP Layer 1 corresponds to OSI Layer 1. TVNP Layer 4 is equivalent to OSI Layer 7.
Structuring the TVNP in such a way means that as future needs and provisions change, aspects of one layer can be enhanced or modified without the need for change to the other layers.
Layer 1 (L1) For serial RS-232 L1 is the Physical Protocol Layer that defines the electrical signals and interconnect requirements at the communication interface port(s) of the CCTV system. V3.0 of the specification allows UDP/IP, typically over Ethernet, to be used for L1. This option is not a physical protocol layer in the OSI sense.
Layer 2 (L2) is the Frame Protocol Layer, sometimes referred to as the Link Layer. Its purpose is to detect and correct errors in the stream of data passing between any two adjacent CCTV systems, so that CCTV network messages are not received in a corrupted form. Layer 2 operates strictly on point-to-point links between adjacent sites and contains no source or destination address information.
Layer 3 (L3) is the Network Protocol Layer, sometimes referred to as the Packet Layer. This is the layer of actual CCTV network messages. The messages have end-to-end significance and contain both source and destination address information.
Layer 4 (L4) is the Application Protocol Layer which makes use of the data network and lower protocol layers to provide services that are required either directly by the users of the system or for system management.

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

- Wikipedia: https://en.wikipedia.org/wiki/TV_Network_Protocol