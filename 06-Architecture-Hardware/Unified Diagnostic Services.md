---
title: "Unified Diagnostic Services"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Unified_Diagnostic_Services"
wikipedia_categories: ["Automotive technologies", "Embedded systems"]
related: ["[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[ATM]]", "[[Automatic system recovery]]", "[[Automotive head-up display]]", "[[Background debug mode interface]]", "[[BasicX]]"]
---

# Unified Diagnostic Services

Unified Diagnostic Services (UDS) is a diagnostic communication protocol used by electronic control units (ECUs) in automotive electronics. UDS is defined by ISO 14229 and evolved from ISO 14230 (KWP2000), which is now largely obsolete. UDS specifies functionality at the session, presentation, and application layers (layers 5–7) of the OSI model. Because of this, it can operate on different physical and data link layers such as CAN (ISO 11898), LIN (ISO 17987), Ethernet (ISO 13400), FlexRay (ISO 17458), and K-Line (ISO 14230). In practice, UDS is most commonly used over CAN via Diagnostic over CAN (DoCAN), defined in ISO 15765.
The term "unified" refers to the fact that UDS is an international standard rather than a manufacturer-specific protocol. Today, nearly all Tier 1 suppliers implement UDS in ECUs developed for automotive original equipment manufacturers (OEMs). UDS is also integrated into larger software architectures, including AUTOSAR.
Modern vehicles have a diagnostic interface for on-board diagnostics, which makes it possible to connect a computer (client) or diagnostics tool, which is referred to as tester, to the communication system of the vehicle. Thus, UDS requests can be sent to the controllers which provide responses (this may be positive or negative). This makes it possible to interrogate the fault memory of the individual control units, to update them with new firmware, have low-level interaction with their hardware (e.g. to turn a specific output on or off), or to make use of special functions (referred to as routines) to attempt to understand the environment and operating conditions of an ECU to be able to diagnose faulty or otherwise undesirable behavior.

## Related

- [[Adesto Technologies]]
- [[ADvantage Framework]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Assembly language]]
- [[ATM]]
- [[Automatic system recovery]]
- [[Automotive head-up display]]
- [[Background debug mode interface]]
- [[BasicX]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unified_Diagnostic_Services