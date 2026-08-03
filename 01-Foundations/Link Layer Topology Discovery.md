---
title: "Link Layer Topology Discovery"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Link_Layer_Topology_Discovery"
wikipedia_categories: ["Link protocols", "Network protocols", "Windows Vista", "Windows communication and services"]
related: ["[[Bonjour Sleep Proxy]]", "[[Discovery and Launch]]", "[[Dynamic synchronous transfer mode]]", "[[Frame Relay]]", "[[G.hn]]", "[[List of products that support SMB]]", "[[LocalTalk]]", "[[Multiple Spanning Tree Protocol]]", "[[NWLink]]", "[[Peer Name Resolution Protocol]]"]
---

# Link Layer Topology Discovery

Link Layer Topology Discovery (LLTD) is a proprietary link layer protocol for network topology discovery and quality of service diagnostics. Microsoft developed it as part of the Windows Rally set of technologies. The LLTD protocol operates over both wired (such as Ethernet (IEEE 802.3) or power line communication) as well as wireless networks (such as IEEE 802.11).
LLTD is included in Windows 7, Windows Vista and Windows 10. It is used by their Network Map feature to display a graphical representation of the local area network (LAN) or wireless LAN (WLAN), to which the computer is connected. Windows XP does not contain the LLTD protocol as a standard component and as a result, Windows XP computers do not appear on the Network Map unless the LLTD responder is installed on Windows XP computers. LLTD is available for download for 32-bit editions of Windows XP with Service Pack 2 (as a publicly released update) and for Windows XP with Service Pack 3 (as a hotfix by request). LLTD Responder was not released for Windows XP Professional x64 Edition. A 2006 fall update for the Xbox 360 enabled support for the LLTD protocol.
Being a link layer (or OSI Layer 2) implementation, LLTD operates strictly on a given local network segment. It cannot discover devices across routers, an operation which would require Internet Protocol level routing.
Link Layer Topology Discovery in Windows Vista consists of two components. The LLTD Mapper I/O component is the master module which controls the discovery process and generates the Network Map. Appropriate permissions for this may be configured with Group Policy settings. It can be allowed or disallowed for domains, and private and public networks. The Mapper sends discovery command packets onto the local network segment via a raw network interface socket. The second component of LLTD are the LLTD Responders which answer Mapper requests about their host and possibly other discovered network information.
In addition to illustrating the layout of a network with representative icons for the hosts and interconnecting lines, each device icon may be explored to produce a popup information box summarizing important network and host parameters, such as MAC address and IP address (both IPv4 and IPv6). Icons are labeled with the hostnames (or first component of their fully qualified domain names), or a representative name of the function of the device, e.g., "gateway". If the device has reported the presence of a management Web interface, clicking on the icon will open a HTTP session to the host.
The LLTD responder for Windows XP only supports reporting of IPv4 addresses and not IPv6.
A royalty free Linux sample implementation of the LLTD responder is available from Microsoft as part of the Windows Rally Development Kit. Using LLTD specifications requires signing a Microsoft Windows Rally license agreement.
There also exists a Perl implementation, using Net::Frame, available via CPAN.

## Related

- [[Bonjour Sleep Proxy]]
- [[Discovery and Launch]]
- [[Dynamic synchronous transfer mode]]
- [[Frame Relay]]
- [[G.hn]]
- [[List of products that support SMB]]
- [[LocalTalk]]
- [[Multiple Spanning Tree Protocol]]
- [[NWLink]]
- [[Peer Name Resolution Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Link_Layer_Topology_Discovery