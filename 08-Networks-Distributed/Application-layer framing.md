---
title: "Application-layer framing"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Application-layer_framing"
wikipedia_categories: ["Computer network stubs", "Internet architecture", "Network performance"]
related: ["[[Adaptive quality of service multi-hop routing]]", "[[AiScaler]]", "[[Application-Layer Protocol Negotiation]]", "[[Bufferbloat]]", "[[Circuit-level gateway]]", "[[DIMES]]", "[[Echo (communications protocol)]]", "[[Fate-sharing]]", "[[Global network positioning]]", "[[Identifier-Locator Network Protocol]]"]
---

# Application-layer framing

Application-layer framing or application-level framing (ALF)  is a method of allowing  an application to use its semantics for the design of its network protocols.
This procedure was first proposed by D. D. Clark and David L. Tennenhouse. It works as follows:

The application splits the data into useful segments.
These segments are called ADUs (application data units).
The ADUs can be processed in any order.
The lower layers keep the ADU borders.
This procedure simplifies the quality of service negotiation and provides a simpler method of error checking.
The Real-time Transport Protocol (RTP) is an example of where the semantics of the real-time application are used to segment the data.

## Related

- [[Adaptive quality of service multi-hop routing]]
- [[AiScaler]]
- [[Application-Layer Protocol Negotiation]]
- [[Bufferbloat]]
- [[Circuit-level gateway]]
- [[DIMES]]
- [[Echo (communications protocol)]]
- [[Fate-sharing]]
- [[Global network positioning]]
- [[Identifier-Locator Network Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Application-layer_framing