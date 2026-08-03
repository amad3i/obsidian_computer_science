---
title: "NAT Port Mapping Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/NAT_Port_Mapping_Protocol"
wikipedia_categories: ["Apple Inc. services", "Apple Inc. stubs", "Computer network stubs", "Network address translation", "Network protocols"]
related: ["[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]", "[[Bearer-Independent Call Control]]", "[[Common Industrial Protocol]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Content Vectoring Protocol]]", "[[ControlNet]]", "[[Digital Audio Access Protocol]]", "[[Digital Data Communications Message Protocol]]"]
---

# NAT Port Mapping Protocol

NAT Port Mapping Protocol (NAT-PMP) is a network protocol for establishing network address translation (NAT) settings and port forwarding configurations automatically without user effort. The protocol automatically determines the external IPv4 address of a NAT gateway, and provides means for an application to communicate the parameters for communication to peers. Apple introduced NAT-PMP in 2005 as part of the Bonjour specification, as an alternative to the more common ISO Standard Internet Gateway Device Protocol implemented in many NAT routers. The protocol was published as an informational Request for Comments (RFC) by the Internet Engineering Task Force (IETF) in RFC 6886.
NAT-PMP runs over the User Datagram Protocol (UDP) and uses port number 5351 on the server, whilst port 5350 is used on the client, as per spec.  It has no built-in authentication mechanisms because forwarding a port typically does not allow any activity that could not also be achieved using STUN methods. The benefit of NAT-PMP over STUN is that it does not require a STUN server and a NAT-PMP mapping has a known expiration time, allowing the application to avoid sending inefficient keep-alive packets.
NAT-PMP is the predecessor of the Port Control Protocol (PCP).

## Related

- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]
- [[Bearer-Independent Call Control]]
- [[Common Industrial Protocol]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Content Vectoring Protocol]]
- [[ControlNet]]
- [[Digital Audio Access Protocol]]
- [[Digital Data Communications Message Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/NAT_Port_Mapping_Protocol