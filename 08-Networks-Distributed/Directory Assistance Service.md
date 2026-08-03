---
title: "Directory Assistance Service"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Directory_Assistance_Service"
wikipedia_categories: ["Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# Directory Assistance Service

The Directory Assistance Service (DAS) is an obsolete protocol and service for accessing X.500 directory services.  DAS was intended to provide a lightweight
means for clients to access X.500 directory services via a split-Directory User Agent model.  Here, the Directory User Agent (DUA) (the directory client) is split into a Directory Assistance (DA) client and a Directory Assistant. The directory user would interact with the DA-client, the DA-Client would communicate with the Directory Assistant using the DA protocol, and the Directory Assistant would communicate with the Directory Service using the X.500 Directory Access Protocol (DAP).  That is, the Directory Assistant is a Directory Assistance protocol to DAP gateway. This design allows the DA-client to access the directory without requiring it to support the cumbersome Open Systems Interconnection protocol stack.
The Directory Assistance Service was created in 1990 by Marshall Rose while at Performance Systems International, Inc., and formally specified in RFC 1202 (published in 1991). It was an evolution of the DISH client/server interface in Quipu, developed by Colin Robbins while at University College London.
These and related efforts, such as DIXIE, led to the development of the Lightweight Directory Access Protocol.  LDAP replaced the Directory Assistance Service.

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

- Wikipedia: https://en.wikipedia.org/wiki/Directory_Assistance_Service