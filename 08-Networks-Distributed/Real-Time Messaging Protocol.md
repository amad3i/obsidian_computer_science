---
title: "Real-Time Messaging Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol"
wikipedia_categories: ["Adobe Flash", "Multimedia", "Network protocols"]
related: ["[[Dynamic Adaptive Streaming over HTTP]]", "[[HTTP Live Streaming]]", "[[Protected Streaming]]", "[[Reliable Internet Stream Transport]]", "[[Access Grid]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[ActionScript]]", "[[Alternating bit protocol]]", "[[AMX192]]"]
---

# Real-Time Messaging Protocol

Real-Time Messaging Protocol (RTMP) is a communication protocol for streaming audio, video, and data over the Internet. Originally developed as a proprietary protocol by Macromedia for streaming between Flash Player and the Flash Communication Server, Adobe (which acquired Macromedia) has released an incomplete version of the specification of the protocol for public use.
The RTMP protocol has multiple variations:

RTMP proper, the "plain" protocol which works on top of Transmission Control Protocol (TCP) and uses port number 1935 by default.
RTMPS, which is RTMP over a Transport Layer Security (TLS/SSL) connection.
RTMPE, which is RTMP encrypted using Adobe's own security mechanism. While the details of the implementation are proprietary, the mechanism uses industry standard cryptographic primitives.
RTMPT, which is encapsulated within HTTP requests to traverse firewalls. RTMPT is frequently found utilizing cleartext requests on TCP ports 80 and 443 to bypass most corporate traffic filtering. The encapsulated session may carry plain RTMP, RTMPS, or RTMPE packets within.
RTMFP, which is RTMP over User Datagram Protocol (UDP) instead of TCP, replacing RTMP Chunk Stream. The Secure Real-Time Media Flow Protocol suite has been developed by Adobe Systems and enables end‐users to connect and communicate directly with each other (P2P).
E-RTMP, or Enhanced RTMP, is an enhancement to the RTMP and FLV specifications designed to improve streaming capabilities while maintaining compatibility with existing RTMP infrastructure. E-RTMP enhances RTMP by adding features such as advanced timestamp precision, multitrack capabilities, expanded codec support, FourCC signaling, and a reconnect request feature.
While the primary motivation for RTMP was to be a protocol for playing Flash Video, it is also used in some other applications, such as the Adobe LiveCycle Data Services ES.

## Related

- [[Dynamic Adaptive Streaming over HTTP]]
- [[HTTP Live Streaming]]
- [[Protected Streaming]]
- [[Reliable Internet Stream Transport]]
- [[Access Grid]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[ActionScript]]
- [[Alternating bit protocol]]
- [[AMX192]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol