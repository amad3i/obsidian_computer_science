---
title: "Remote Audio Output Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Remote_Audio_Output_Protocol"
wikipedia_categories: ["Data transmission", "Network protocols"]
related: ["[[Acknowledgement (data networks)]]", "[[Communication protocol]]", "[[Comparison of MQTT implementations]]", "[[Digital Audio Access Protocol]]", "[[Digital Media Access Protocol]]", "[[Encapsulation (networking)]]", "[[Handshake (computing)]]", "[[Identity Registration Protocol]]", "[[IF-MAP]]", "[[MQTT]]"]
---

# Remote Audio Output Protocol

Remote Audio Output Protocol (RAOP) is an Internet streaming protocol based on RTSP / RTP authored by Apple Inc. It powers the AirPlay technology built into AirPort Express wireless (802.11b/g/n) access point as well as the Apple TV.
The major difference from RTSP is an initial asymmetric key verification made by iTunes to verify it is communicating with an AirPort Express or an Apple TV (as opposed to a simulation), and vice versa. The data channel is also encrypted by AES, with a random key protected by the asymmetric key mentioned above.
The RSA public key stored in iTunes was extracted by Jon Lech Johansen, enabling third-party software to stream music to an AirPort Express.
The RSA private key stored in the AirPort Express was extracted by James Laird, enabling simulation of an Airport Express.
The Shairport-sync application which emulates Airport Express hardware is available.

## Related

- [[Acknowledgement (data networks)]]
- [[Communication protocol]]
- [[Comparison of MQTT implementations]]
- [[Digital Audio Access Protocol]]
- [[Digital Media Access Protocol]]
- [[Encapsulation (networking)]]
- [[Handshake (computing)]]
- [[Identity Registration Protocol]]
- [[IF-MAP]]
- [[MQTT]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Remote_Audio_Output_Protocol