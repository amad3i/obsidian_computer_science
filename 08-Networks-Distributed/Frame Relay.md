---
title: "Frame Relay"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Frame_Relay"
wikipedia_categories: ["Frame Relay", "Link protocols", "Network protocols"]
related: ["[[Bonjour Sleep Proxy]]", "[[Dynamic synchronous transfer mode]]", "[[G.hn]]", "[[Link Layer Topology Discovery]]", "[[LocalTalk]]", "[[Multiple Spanning Tree Protocol]]", "[[Resilient Ethernet Protocol]]", "[[Spanning Tree Protocol]]", "[[Virtual Link Aggregation Control Protocol]]", "[[Virtual Link Trunking]]"]
---

# Frame Relay

Frame Relay (FR) is a standardized wide area network (WAN) technology that specifies the physical and data link layers of digital telecommunications channels using a packet switching methodology.
Frame Relay was originally developed as a simplified version of the X.25 system designed to be carried over the emerging Integrated Services Digital Network (ISDN) networks. X.25 had been designed to operate over normal telephone lines that were subject to noise that would result in lost data, and the protocol featured extensive error correction to address this. ISDN offered dramatically lower error rates, in effect zero, and the extensive error correction overhead was no longer needed. The new protocol suite was essentially a cut-down X.25 with no error correction, leading to lower overhead, better channel efficiency, and often significantly overall higher performance than X.25.
Like X.25, Frame Relay is normally used in a circuit switched layout, where connections between two endpoints are long-term (in computer terms at least). This matches the normal use of the telephone network, which X.25 was designed to run on top of. This contrasts with protocols design to be short-term, like the internet Protocol, where every packet might go to a different endpoint. In practice, Frame Relay was often used as a bridging mechanism to link together local area network (LAN) systems or devices with dedicated links to back-end systems. Users are provided with a connection that encapsulates their data (in some cases including voice in VoFR) and sends that to a Frame Relay node which then forwards that to another endpoint where it is injected into the remote network, appearing as if it were local traffic. It is less expensive than using leased lines for this purpose and that is one reason for its popularity. The extreme simplicity of configuring user equipment in a Frame Relay network offers another reason for Frame Relay's popularity.
With the advent of Ethernet over fiber optics, MPLS, VPN and dedicated broadband services such as cable modem and DSL, Frame Relay has become less popular in recent years.
The Frame Relay standards were promoted by the Frame Relay Forum (FRF).

## Related

- [[Bonjour Sleep Proxy]]
- [[Dynamic synchronous transfer mode]]
- [[G.hn]]
- [[Link Layer Topology Discovery]]
- [[LocalTalk]]
- [[Multiple Spanning Tree Protocol]]
- [[Resilient Ethernet Protocol]]
- [[Spanning Tree Protocol]]
- [[Virtual Link Aggregation Control Protocol]]
- [[Virtual Link Trunking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Frame_Relay