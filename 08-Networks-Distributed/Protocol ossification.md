---
title: "Protocol ossification"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Protocol_ossification"
wikipedia_categories: ["Network protocols", "Tragedy of the commons"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Protocol ossification

Protocol ossification is the loss of flexibility, extensibility and evolvability of network protocols. This is largely due to middleboxes that are sensitive to the wire image of the protocol, and which can interrupt or interfere with messages that are valid but which the middlebox does not correctly recognise. This is a violation of the end-to-end principle. Secondary causes include inflexibility in endpoint implementations of protocols. 
Ossification is a major issue in Internet protocol design and deployment, as it can prevent new protocols or extensions from being deployed on the Internet, or place strictures on the design of new protocols; new protocols may have to be encapsulated in an already-deployed protocol or mimic the wire image of another protocol. Because of ossification, the Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) are the only practical choices for transport protocols on the Internet, and TCP itself has significantly ossified, making extension or modification of the protocol difficult. 
Recommended methods of preventing ossification include encrypting protocol metadata, and ensuring that extension points are exercised and wire image variability is exhibited as fully as possible; remedying existing ossification requires coordination across protocol participants. QUIC is the first IETF transport protocol to have been designed with deliberate anti-ossification properties.

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

- Wikipedia: https://en.wikipedia.org/wiki/Protocol_ossification