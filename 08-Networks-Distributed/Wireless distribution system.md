---
title: "Wireless distribution system"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Wireless_distribution_system"
wikipedia_categories: ["IEEE 802.11", "Wireless networking"]
related: ["[[CCMP (cryptography)]]", "[[Complementary code keying]]", "[[Control and Provisioning of Wireless Access Points protocol]]", "[[Direct-sequence spread spectrum]]", "[[Exposed node problem]]", "[[Hidden node problem]]", "[[IEEE 802.11ad]]", "[[IEEE 802.11af]]", "[[Morse Micro]]", "[[Temporal Key Integrity Protocol]]"]
---

# Wireless distribution system

A wireless distribution system (WDS) is a system enabling the wireless interconnection of access points in an IEEE 802.11 network. It allows a wireless network to be expanded using multiple access points without the traditional requirement for a wired backbone to link them. The notable advantage of WDS over other solutions is that it preserves the MAC addresses of client frames across links between access points.
An access point can be either a main, relay, or remote base station.

A main base station is typically connected to the (wired) Ethernet.
A relay base station relays data between remote base stations, wireless clients, or other relay stations; to either a main, or another relay base station.
A remote base station accepts connections from wireless clients and passes them on to relay stations or to main stations. Connections between "clients" are made using MAC addresses.
All base stations in a wireless distribution system must be configured to use the same radio channel, method of encryption (none, WEP, WPA or WPA2) and the same encryption keys. They may be configured to different service set identifiers (SSIDs). WDS also requires every base station to be configured to forward to others in the system.
WDS may also be considered a repeater mode because it appears to bridge and accept wireless clients at the same time (unlike traditional bridging). However, with the repeater method, throughput is halved for all clients connected wirelessly. This is because Wi-Fi is an inherently half duplex medium and therefore any Wi-Fi device functioning as a repeater must use the Store and forward method of communication.
WDS may be incompatible between different products (even occasionally from the same vendor) since the IEEE 802.11-1999 standard does not define how to construct any such implementations or how stations interact to arrange for exchanging frames of this format. The IEEE 802.11-1999 standard merely defines the 4-address frame format that makes it possible.

## Related

- [[CCMP (cryptography)]]
- [[Complementary code keying]]
- [[Control and Provisioning of Wireless Access Points protocol]]
- [[Direct-sequence spread spectrum]]
- [[Exposed node problem]]
- [[Hidden node problem]]
- [[IEEE 802.11ad]]
- [[IEEE 802.11af]]
- [[Morse Micro]]
- [[Temporal Key Integrity Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Wireless_distribution_system