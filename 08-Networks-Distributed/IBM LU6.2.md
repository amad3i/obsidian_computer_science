---
title: "IBM LU6.2"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IBM_LU6.2"
wikipedia_categories: ["IBM software", "Network protocols", "Systems Network Architecture"]
related: ["[[IBM Advanced Peer-to-Peer Networking]]", "[[IBM Advanced Program-to-Program Communication]]", "[[IBM Network Control Program]]", "[[Systems Network Architecture]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Address constant]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[APL (programming language)]]"]
---

# IBM LU6.2

Logical Unit 6.2 is an IBM-originated communications protocol specification dating from 1974, and is part of IBM's Systems Network Architecture (SNA).
A device-independent SNA protocol, it is used for peer-to-peer communications between two systems, for example, between a computer and a device (e.g. terminal or printer), or between computers. LU6.2 is used by many of IBM's products, including Common Programming Interface for Communications Intersystem Communications (CICS ISC), and Information Management System, and also many non-IBM products. In 1986, Bruce Compton, Manager of Office Systems and Technology with General Electric, said:

LU 6.2 means I don't have to write the software communications interfaces. If I have one office server in a DEC environment, and another in a Wang environment... I can use the LU 6.2 standard to pass files between those devices, and I don't have to worry about things like block checking and clock.

Some examples of non-IBM products which implemented the SNA stack including LU6.2 are: Microsoft Host Integration Server, and NetWare for SAA.
APPC is a protocol used with LU6.2 architecture. APPC is often used to refer to the LU6.2 architecture or to specific LU6.2 features.
LU6.2-compliant devices operate as peers within the network and can perform multiple simultaneous transactions over the network. LU6.2 devices can also detect and correct errors. The LU6.2 definition provides a common API for communicating with and controlling compliant devices. Although the concepts were the same on all platforms, the actual API implementation often varied on each IBM platform which implemented it. Other vendors also implemented LU6.2 in their own products and with their own APIs. IBM later defined the Common Programming Interface for Communications (CPIC) API which would eventually become widely implemented. CPIC allowed for the authoring of multi-platform code.
Adoption was slow but steady. As of November 1987, of 207 large US companies interviewed  "Eighteen percent of the companies said they have implemented LU 6.2 systems already, and 51% said they expect to have such systems up and running within two years."

## Related

- [[IBM Advanced Peer-to-Peer Networking]]
- [[IBM Advanced Program-to-Program Communication]]
- [[IBM Network Control Program]]
- [[Systems Network Architecture]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Address constant]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[APL (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IBM_LU6.2