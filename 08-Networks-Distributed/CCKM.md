---
title: "CCKM"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/CCKM"
wikipedia_categories: ["Computer network stubs", "Wireless networking"]
related: ["[[Augmented tree-based routing]]", "[[DataTAC]]", "[[Fuzzy routing]]", "[[Gi-Fi]]", "[[MMARP]]", "[[NetStumbler]]", "[[ODMRP]]", "[[Radio Link Protocol]]", "[[SecureEasySetup]]", "[[Wireless LAN controller]]"]
---

# CCKM

Cisco Centralized Key Management (CCKM) is a form of Fast Roaming and a subset of the Cisco Compatible EXtensions (CCX) specification. 
When a wireless LAN is configured for fast reconnection, a Lightweight Extensible Authentication Protocol (LEAP) enabled client device can roam from one wireless access point to another without involving the main server. Using CCKM, an access point configured to provide Wireless Domain Services (WDS) takes the place of the RADIUS server, and authenticates the client without perceptible delay in voice or other time-sensitive applications.
The WDS (which can be run as a service on a Cisco Access Point or on various router modules) caches the user credentials after the initial log-on. The user must authenticate with the Radius server the first time – then they can roam between access points using cached credentials. This saves time in the roaming process, especially valuable for VoIP devices.
The current implementation of CCKM requires Cisco compatible hardware and either LEAP, EAP-FAST (CCXv3) or PEAP-GTC, PEAP-MSCHAP, EAP-TLS (CCXv4).

## Related

- [[Augmented tree-based routing]]
- [[DataTAC]]
- [[Fuzzy routing]]
- [[Gi-Fi]]
- [[MMARP]]
- [[NetStumbler]]
- [[ODMRP]]
- [[Radio Link Protocol]]
- [[SecureEasySetup]]
- [[Wireless LAN controller]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CCKM