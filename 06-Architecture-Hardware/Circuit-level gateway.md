---
title: "Circuit-level gateway"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Circuit-level_gateway"
wikipedia_categories: ["Computer network stubs", "Internet architecture", "Network socket", "Transmission Control Protocol"]
related: ["[[Application-layer framing]]", "[[DIMES]]", "[[Echo (communications protocol)]]", "[[Fate-sharing]]", "[[Global network positioning]]", "[[Identifier-Locator Network Protocol]]", "[[IP aliasing]]", "[[Management plane]]", "[[Per-hop behaviour]]", "[[QPPB]]"]
---

# Circuit-level gateway

A circuit-level gateway is a type of firewall.
Circuit-level gateways work at the session layer of the OSI model, or as a "shim-layer" between the application layer and the transport layer of the TCP/IP stack. They monitor TCP handshaking between packets to determine whether a requested session is legitimate. Information passed to a remote computer through a circuit-level gateway appears to have originated from the gateway. Firewall traffic is cleaned based on particular session rules and may be controlled to acknowledged computers only. Circuit-level firewalls conceal the details of the protected network from the external traffic, which is helpful for interdicting access to impostors. Circuit-level gateways are relatively inexpensive and have the advantage of hiding information about the private network they protect. However, they do not filter individual packets.

## Related

- [[Application-layer framing]]
- [[DIMES]]
- [[Echo (communications protocol)]]
- [[Fate-sharing]]
- [[Global network positioning]]
- [[Identifier-Locator Network Protocol]]
- [[IP aliasing]]
- [[Management plane]]
- [[Per-hop behaviour]]
- [[QPPB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Circuit-level_gateway