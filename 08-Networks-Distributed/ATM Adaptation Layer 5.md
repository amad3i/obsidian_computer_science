---
title: "ATM Adaptation Layer 5"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/ATM_Adaptation_Layer_5"
wikipedia_categories: ["Asynchronous Transfer Mode", "Network protocols"]
related: ["[[ATM Adaptation Layer 2]]", "[[Available bit rate]]", "[[CRC-based framing]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]"]
---

# ATM Adaptation Layer 5

ATM Adaptation Layer 5 (AAL5) is an ATM adaptation layer used to send variable-length packets up to 65,535 octets in size across an Asynchronous Transfer Mode (ATM) network.
Unlike most network frames, which place control information in the header, AAL5 places control information in an 8-octet trailer at the end of the packet. The AAL5 trailer contains a 16-bit length field, a 32-bit cyclic redundancy check (CRC) and two 8-bit fields labeled UU and CPI that are currently unused.
Each AAL5 packet is divided into an integral number of ATM cells and reassembled into a packet before delivery to the receiving host. This process is known as Segmentation and Reassembly (see below). The last cell contains padding to ensure that the entire packet is a multiple of 48 octets long. The final cell contains up to 40 octets of data, followed by padding bytes and the 8-octet trailer. In other words, AAL5 places the trailer in the last 8 octets of the final cell where it can be found without knowing the length of the packet; the final cell is identified by a bit in the ATM header (see below), and the trailer is always in the last 8 octets of that cell.

## Related

- [[ATM Adaptation Layer 2]]
- [[Available bit rate]]
- [[CRC-based framing]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ATM_Adaptation_Layer_5