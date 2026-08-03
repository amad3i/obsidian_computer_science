---
title: "Radio Link Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Radio_Link_Protocol"
wikipedia_categories: ["Computer network stubs", "Link protocols", "Radio resource management", "Wireless networking", "Wireless stubs"]
related: ["[[Augmented tree-based routing]]", "[[CCKM]]", "[[Cognitive radio]]", "[[Communication Linking Protocol]]", "[[Control and Provisioning of Wireless Access Points protocol]]", "[[DataTAC]]", "[[Detect and avoid]]", "[[Dynamic single-frequency networks]]", "[[Fuzzy routing]]", "[[Gi-Fi]]"]
---

# Radio Link Protocol

Radio Link Protocol (RLP) is an automatic repeat request (ARQ) fragmentation protocol used over a wireless (typically cellular) air interface. RLP occurs on the data link layer (Layer 2) of the OSI networking model.
Most wireless air interfaces are tuned to provide 1% packet loss, and most vocoders are mutually tuned to sacrifice very little voice quality at 1% packet loss. However, 1% packet loss is intolerable to all variants of TCP, and so something must be done to improve reliability for voice networks carrying TCP/IP data. A RLP detects packet losses and performs retransmissions to bring packet loss down to approximately .01%, or even .0001%, which is suitable for TCP/IP applications. When the receiver detects a missed packet, it sends a NAK (not acknowledged) frame to the sender, which triggers a retransmission of the missing packet. At the same time, the receiver sets a timer for receipt of the missing packet. Each time the timer expires without receipt of the packet, the receiver resets the timer and sends NAK a number of times equal to 1 + the number of times the timer has already expired, up to a limit. 
RLP also implements stream fragmentation and reassembly, and sometimes, in-order delivery. Some forms of RLP rely upon a higher-layer PPP protocol to provide these functions, while newer forms of RLP also provide framing and compression.
Because a CDMA IS-95 network's smallest voice packet size (and thus an RLP packet length) can be as little as 88 bits (11 bytes), RLP headers must be very small, to minimize overhead. This is typically achieved by allowing both ends to negotiate a variable 'sequence number space', which is used to number each byte in the transmission stream. In some variants of RLP, this sequence counter can be as small as 6 bits
A RLP transport cannot ask the air interface to provide a certain payload size. Instead, the air interface scheduler determines the packet size, based upon constantly changing channel conditions, and upcalls RLP with the chosen packet payload size, right before transmission. Most other fragmentation protocols, such as those of 802.11b and IP, used payload sizes determined by the upper layers, and call upon the MAC to create a payload of a certain size. These other protocols are not as flexible as RLP and can sometimes fail to transmit during a deep fade in a wireless environment.
A RLP protocol can be ACK-based or NAK-based. Most RLPs are NAK-based, meaning that forward-link sender assumes that each transmission got through, and the receiver only NAKs when an out-of-order segment is received. This greatly reduces reverse-link transmissions, which are spectrally inefficient and have a longer latency on most cellular networks. When the transmit pipeline goes idle, a NAK-based RLP must eventually retransmit the last segment a second time, in case the last fragment was lost, to reach a .01% packet loss rate. This duplicate transmission is typically controlled by a "flush timer" set to expire 200-500 milliseconds after the channel goes idle.
The concept of a RLP protocol was invented by Phil Karn with Qualcomm in 1993 for CDMA (IS-95) networks.
The January 2006 IEEE 802.20 specification uses a form of RLP.
Cellular networks such as GSM and CDMA use different variations of RLP. In UMTS and in LTE, the protocol is called RLC (Radio Link Control).

## Related

- [[Augmented tree-based routing]]
- [[CCKM]]
- [[Cognitive radio]]
- [[Communication Linking Protocol]]
- [[Control and Provisioning of Wireless Access Points protocol]]
- [[DataTAC]]
- [[Detect and avoid]]
- [[Dynamic single-frequency networks]]
- [[Fuzzy routing]]
- [[Gi-Fi]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Radio_Link_Protocol