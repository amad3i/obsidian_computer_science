---
title: "Constraint-based Routing Label Distribution Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Constraint-based_Routing_Label_Distribution_Protocol"
wikipedia_categories: ["Computer network stubs", "MPLS networking", "Network protocols"]
related: ["[[Router alert label]]", "[[Automatic switched-transport network]]", "[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]", "[[Bearer-Independent Call Control]]", "[[Common Industrial Protocol]]", "[[Constrained Shortest Path First]]", "[[Content Vectoring Protocol]]", "[[ControlNet]]"]
---

# Constraint-based Routing Label Distribution Protocol

Constraint-based Routing Label Distribution Protocol (CR-LDP) is a control protocol used in some computer networks.
As of February 2003, the IETF MPLS working group deprecated CR-LDP and decided to focus purely on RSVP-TE.
It is an extension of the Label Distribution Protocol (LDP), one of the protocols in the Multiprotocol Label Switching architecture. CR-LDP contains extensions for LDP to extend its capabilities such as setup paths beyond what is available for the routing protocol. For instance, a label-switched path can be set up based on explicit route constraints, quality of service constraints, and other constraints. Constraint-based routing (CR) is a mechanism used to meet traffic engineering requirements. These requirements are met by extending LDP for support of constraint-based routed label-switched paths (CR-LSPs). Other uses for CR-LSPs include MPLS-based virtual private networks.
CR-LDP is almost same as basic LDP, in packet structure, but it contains some extra TLVs which basically set up the constraint-based LSP.

## Related

- [[Router alert label]]
- [[Automatic switched-transport network]]
- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]
- [[Bearer-Independent Call Control]]
- [[Common Industrial Protocol]]
- [[Constrained Shortest Path First]]
- [[Content Vectoring Protocol]]
- [[ControlNet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constraint-based_Routing_Label_Distribution_Protocol