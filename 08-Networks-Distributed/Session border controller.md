---
title: "Session border controller"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Session_border_controller"
wikipedia_categories: ["Computer network security", "Voice over IP"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Session border controller

A session border controller (SBC) is a network element deployed to protect SIP-based VoIP networks.
Early deployments of SBCs were focused on the borders between two service provider networks in a peering environment. This role has since expanded to include significant deployments between a service provider's access network and its backbone network, providing service to residential and/or enterprise customers.
The term "session" refers to a communication between two or more parties – in the context of telephony, this would be a call. Each call consists of one or more call signaling message exchanges that control the call, and one or more call media streams which carry the call's audio, video, or other data along with information of call statistics and quality. Together, these streams make up a session. It is the job of a session border controller to exert influence over the data flows of sessions.
The term "border" refers to a point of demarcation between one part of a network and another. As a simple example, at the edge of a corporate network, a firewall demarcates the local network (inside the corporation) from the rest of the Internet (outside the corporation). A more complex example is that of a large corporation where different departments have security needs for each location and perhaps for each kind of data. In this case, filtering routers or other network elements are used to control the flow of data streams. It is the job of a session border controller to assist policy administrators in managing the flow of session data across these borders.
The term "controller" refers to the influence that session border controllers have on the data streams that comprise sessions, as they traverse borders between one part of a network and another. Additionally, session border controllers often provide measurement, access control, and data conversion facilities for the calls they control.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Session_border_controller