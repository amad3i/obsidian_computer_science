---
title: "Bearer-Independent Call Control"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Bearer-Independent_Call_Control"
wikipedia_categories: ["Computer network stubs", "Network protocols"]
related: ["[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]", "[[Common Industrial Protocol]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Content Vectoring Protocol]]", "[[ControlNet]]", "[[Digital Data Communications Message Protocol]]", "[[DREAM (protocol)]]", "[[ERIPAX]]"]
---

# Bearer-Independent Call Control

The Bearer-Independent Call Control (BICC) is a signaling protocol based on N-ISUP that is used for supporting narrowband Integrated Services Digital Network (ISDN) service over a broadband backbone network.  BICC is designed to interwork with existing transport technologies. BICC is specified in ITU-T recommendation Q.1901.
BICC signaling messages are nearly identical to those in ISDN User Part (ISUP); the main difference being that the narrowband circuit identification code (CIC) has been modified.  The BICC architecture consists of interconnected serving nodes that provide the call service function and the bearer control function.  The call service function uses BICC signaling for call setup and may also interwork with ISUP.  The bearer control function receives directives from the call service function via BICC Bearer Control Protocol (ITU-T recommendation Q.1950) and is responsible for setup and teardown of bearer paths on a set of physical transport links.  Transport links are most commonly Asynchronous Transfer Mode (ATM) or Internet Protocol (IP).   
According to the ITU, the completion of the BICC protocols is a historic step toward broadband multimedia networks because it enables the seamless migration from circuit-switched TDM networks to high-capacity broadband multimedia networks.
The Third-Generation Partnership Project (3GPP) has included BICC CS 2 in the Universal Mobile Telecommunications System (UMTS) release 4.

## Related

- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]
- [[Common Industrial Protocol]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Content Vectoring Protocol]]
- [[ControlNet]]
- [[Digital Data Communications Message Protocol]]
- [[DREAM (protocol)]]
- [[ERIPAX]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bearer-Independent_Call_Control