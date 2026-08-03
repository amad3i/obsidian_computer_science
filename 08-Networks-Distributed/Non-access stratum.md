---
title: "Non-access stratum"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Non-access_stratum"
wikipedia_categories: ["Mobile technology", "Network protocols", "Technology stubs"]
related: ["[[Access stratum]]", "[[CIMD]]", "[[EMI (protocol)]]", "[[PFCP]]", "[[Short Message Peer-to-Peer]]", "[[Telocator Alphanumeric Protocol]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]"]
---

# Non-access stratum

Non-access stratum (NAS) is a functional layer in the NR, LTE, UMTS and GSM wireless telecom protocol stacks between the core network and user equipment. 
This layer is used to manage the establishment of communication sessions and for maintaining continuous communications with the user equipment as it moves.  The NAS is defined in contrast to the Access Stratum which is responsible for carrying information over the wireless portion of the network.
A further description of NAS is that it is a protocol for messages passed between the User Equipment, also known as mobiles, and Core Nodes (e.g. Mobile Switching Center, Serving GPRS Support Node, or Mobility Management Entity) that is passed transparently through the radio network. Examples of NAS messages include Update or Attach messages, Authentication Messages, Service Requests and so forth.  Once the User Equipment (UE) establishes a radio connection, the UE uses the radio connection to communicate with the core nodes to coordinate service.  The distinction is that the Access Stratum is for dialogue explicitly between the mobile equipment and the radio network and the NAS is for dialogue between the mobile equipment and core network nodes. 
For LTE, the Technical Specification for NAS is 3GPP TS 24.301. For NR, the Technical Specification for NAS is TS 24.501.

+- – - – - -+       +- – - – - – -+
| HTTP      |       | Application |
+- – - – - -+       +- – - – - – -+
| TCP       |       | Transport   |
+- – - – - -+       +- – - – - – -+
| IP        |       | Internet    |
+- – - – - -+       +- – - – - – -+
| NAS       |       | Network     |
+- – - – - -+       +- – - – - – -+
| AS        |       | Link        |
+- – - – - -+       +- – - – - – -+
| Channels  |       | Physical    |
+- – - – - -+       +- – - – - – -+

## Related

- [[Access stratum]]
- [[CIMD]]
- [[EMI (protocol)]]
- [[PFCP]]
- [[Short Message Peer-to-Peer]]
- [[Telocator Alphanumeric Protocol]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Non-access_stratum