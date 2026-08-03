---
title: "MacIP"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/MacIP"
wikipedia_categories: ["Internet protocols", "Macintosh operating systems APIs", "Network layer protocols"]
related: ["[[ICMPv6]]", "[[Identifier-Locator Network Protocol]]", "[[Internet Control Message Protocol]]", "[[Internet Group Management Protocol]]", "[[IPsec]]", "[[Multicast Listener Discovery]]", "[[Named data networking]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]"]
---

# MacIP

MacIP is a standard for encapsulating Internet Protocol (IP) packets within the AppleTalk Datagram Delivery Protocol (DDP), as LocalTalk only carries AppleTalk (unlike Ethernet, which carries multiple higher-layer protocols natively and simultaneously). This allows Macintosh computers with LocalTalk networking hardware to access TCP/IP-based network services, typically over Ethernet. This was an important bridging technology during the era when Ethernet and TCP/IP were rapidly growing in popularity in the early 1990s.
Software implementing MacIP, such as MacTCP or Open Transport, was installed on the computer, and a MacIP Gateway was placed elsewhere on the network. Applications that communicate through TCP/IP (such as Telnet) have their IP packets encapsulated in DDP, to carry IP in AppleTalk across the LocalTalk network to the MacIP Gateway. The MacIP Gateway strips off the DDP encapsulation and forwards the IP packet on the IP network.
The gateways were often implemented as part of a LocalTalk-to-Ethernet bridge device, small hardware systems primarily designed to allow communications between LocalTalk and EtherTalk equipped AppleTalk machines (like the Mac II and a LaserWriter). MacIP routing was often implemented as an optional adjunct to the AppleTalk routing. Cisco Systems supported AppleTalk in their proprietary IOS (up to and including version 12.4(15)T14, on select platforms) which in turn could provide MacIP-Services.

## Related

- [[ICMPv6]]
- [[Identifier-Locator Network Protocol]]
- [[Internet Control Message Protocol]]
- [[Internet Group Management Protocol]]
- [[IPsec]]
- [[Multicast Listener Discovery]]
- [[Named data networking]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MacIP