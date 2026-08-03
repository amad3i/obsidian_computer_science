---
title: "Session Announcement Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Session_Announcement_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]"]
---

# Session Announcement Protocol

The Session Announcement Protocol (SAP) is an experimental protocol for advertising multicast session information. SAP typically uses Session Description Protocol (SDP) as the format for Real-time Transport Protocol (RTP) session descriptions. Announcement data is sent using IP multicast and the User Datagram Protocol (UDP).
Under SAP, senders periodically transmit SDP descriptions to a well-known multicast address and port number (9875). A listening application constructs a guide of all advertised multicast sessions.
SAP was published by the IETF as RFC 2974.

## Related

- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]
- [[Directory information tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Session_Announcement_Protocol