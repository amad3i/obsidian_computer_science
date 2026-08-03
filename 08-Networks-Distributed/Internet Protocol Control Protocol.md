---
title: "Internet Protocol Control Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Internet_Protocol_Control_Protocol"
wikipedia_categories: ["Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# Internet Protocol Control Protocol

In computer networking, Internet Protocol Control Protocol (IPCP) is a Network Control Protocol (NCP) for establishing and configuring Internet Protocol over a Point-to-Point Protocol link. IPCP is responsible for configuring the IP addresses as well as for enabling and disabling the IP protocol modules on both ends of the point-to-point link. IPCP uses the same packet exchange mechanism as the Link Control Protocol. IPCP packets may not be exchanged until PPP has reached the Network-Layer Protocol phase, and any IPCP packets received before this phase is reached should be silently discarded. IPCP has the NCP protocol code number 0x8021.
Each of the two endpoints of a PPP connection must send an IPCP configure request to its peer because the TCP/IP options are independent for each direction of a PPP connection.
A PPP endpoint can request a specific IP address from its peer. It can also ask the peer to suggest an IP address by requesting the address 0.0.0.0; the peer then sends its suggestion in an IPCP Nak packet, which the first peer must subsequently request in order to complete the negotiation. In practice, in protocols like PPPoE which is commonly used in home broadband connections, the latter method (request suggestion, nak with suggestion, request suggested address) is used to set the IP address of the Internet service provider's (ISP's) client endpoint (i.e., the customer-premises equipment), while the former method (request address) is used to inform the client of the ISP endpoint IP (provider edge equipment).
A similar NCP, the IPv6 Control Protocol exists for IPv6. It can be used together with IPCP on the same PPP connection for a dual stack link. (When interfacing newer and older equipment that doesn't support IPv6 one sees LCP ProtRej messages for protocol 0x8057 from the side that doesn't support IPV6CP.)

## Related

- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Internet_Protocol_Control_Protocol