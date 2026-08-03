---
title: "Deterministic Networking"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Deterministic_Networking"
wikipedia_categories: ["Audio engineering", "Automotive electronics", "Control engineering"]
related: ["[[Time-Sensitive Networking]]", "[[Ackermann's formula]]", "[[ADMAR]]", "[[Almost periodic function]]", "[[American Automatic Control Council]]", "[[Audio normalization]]", "[[Audio time stretching and pitch scaling]]", "[[Blackman's theorem]]", "[[Campbell diagram]]", "[[CIMACT]]"]
---

# Deterministic Networking

Deterministic Networking (DetNet) is an effort by the IETF DetNet Working Group to study implementation of deterministic data paths for real-time applications with extremely low data loss rates, packet delay variation (jitter), and bounded latency, such as audio and video streaming, industrial automation, and vehicle control. 
DetNet operates at the IP Layer 3 routed segments using a software-defined networking layer to provide IntServ and DiffServ integration, and delivers service over lower Layer 2 bridged segments using technologies such as MPLS and IEEE 802.1 Time-Sensitive Networking. Deterministic Networking aims to migrate time-critical, high-reliability industrial control and audio-video applications from special-purpose Fieldbus networks (HDMI, CAN bus, PROFIBUS, RS-485, RS-422/RS-232, and I²C) to packet networks and IP in particular. DetNet will support both the new applications and existing IT applications on the same physical network.
To support real-time applications, DetNet implements reservation of data plane resources in intermediate nodes along the data flow path, calculation of explicit routes that do not depend on network topology, and redistribute data packets over time and/or space to deliver data even with the loss of one path.

## Related

- [[Time-Sensitive Networking]]
- [[Ackermann's formula]]
- [[ADMAR]]
- [[Almost periodic function]]
- [[American Automatic Control Council]]
- [[Audio normalization]]
- [[Audio time stretching and pitch scaling]]
- [[Blackman's theorem]]
- [[Campbell diagram]]
- [[CIMACT]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deterministic_Networking