---
title: "GPRS Tunnelling Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/GPRS_Tunnelling_Protocol"
wikipedia_categories: ["3GPP standards", "GSM standard", "Mobile telecommunications standards", "Network protocols", "Tunneling protocols"]
related: ["[[PFCP]]", "[[RANAP]]", "[[BSSGP]]", "[[CIMD]]", "[[Distributed Overlay Virtual Ethernet]]", "[[EMI (protocol)]]", "[[HTTP tunnel]]", "[[MPLS-TP]]", "[[Overlay transport virtualization]]", "[[Router alert label]]"]
---

# GPRS Tunnelling Protocol

GPRS Tunnelling Protocol (GTP) is a group of IP-based communications protocols used to carry general packet radio service (GPRS) within GSM, UMTS, LTE and 5G NR radio networks. In 3GPP architectures, GTP and Proxy Mobile IPv6 based interfaces are specified on various interface points.
GTP can be decomposed into separate protocols, GTP-C, GTP-U and GTP'.
GTP-C is used within the GPRS core network for signaling between gateway GPRS support nodes (GGSN) and serving GPRS support nodes (SGSN).  This allows the SGSN to activate a session on a user's behalf (PDP context activation), to deactivate the same session, to adjust quality of service parameters, or to update a session for a subscriber who has just arrived from another SGSN.
GTP-U is used for carrying user data within the GPRS core network and between the radio access network and the core network.  The user data transported can be packets in any of IPv4, IPv6, or PPP formats.
GTP' (GTP prime) uses the same message structure as GTP-C and GTP-U, but has an independent function. It can be used for carrying charging data from the charging data function (CDF) of the GSM or UMTS network to the charging gateway function (CGF). In most cases, this should mean from many individual network elements such as the GGSNs to a centralized computer that delivers the charging data more conveniently to the network operator's billing center.
Different GTP variants are implemented by RNCs, SGSNs, GGSNs and CGFs within 3GPP networks. GPRS mobile stations (MSs) are connected to a SGSN without being aware of GTP.
GTP can be used with UDP or TCP. UDP is either recommended or mandatory, except for tunnelling X.25 in version 0. GTP version 1 is used only on UDP.

## Related

- [[PFCP]]
- [[RANAP]]
- [[BSSGP]]
- [[CIMD]]
- [[Distributed Overlay Virtual Ethernet]]
- [[EMI (protocol)]]
- [[HTTP tunnel]]
- [[MPLS-TP]]
- [[Overlay transport virtualization]]
- [[Router alert label]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GPRS_Tunnelling_Protocol