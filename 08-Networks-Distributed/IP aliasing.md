---
title: "IP aliasing"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IP_aliasing"
wikipedia_categories: ["Computer network stubs", "Internet architecture"]
related: ["[[Application-layer framing]]", "[[Circuit-level gateway]]", "[[DIMES]]", "[[Echo (communications protocol)]]", "[[Fate-sharing]]", "[[Global network positioning]]", "[[Identifier-Locator Network Protocol]]", "[[Management plane]]", "[[Per-hop behaviour]]", "[[QPPB]]"]
---

# IP aliasing

IP aliasing is associating more than one IP address to a network interface. With this, one node on a network can have multiple connections to a network, each serving a different purpose.

According to the Linux Kernel documentation, IP-aliases are an obsolete way to manage multiple IP-addresses/masks per interface. Newer tools such as iproute2 support multiple address/prefixes per interface, but aliases are still supported for backwards compatibility.
In the Linux kernel, it was first implemented by Juan José Ciarlante in 1995. On Solaris IP aliasing was called logical network interface and was first available in Solaris 2.5 in 1995. It has also been possible in Microsoft Windows NT since (at least) Windows NT 3.51, released in 1995.
IP aliasing can be used to provide multiple network addresses on a single physical interface. This demonstrates using IP version 4 addresses only. One reason for using this could be to make a computer look as though it is multiple computers, so for example you could have one server that is acting as both a gateway (router) and a DHCP server and DNS using three different IP addresses, perhaps with a future plan to use a hardware router and to move the functionality to separate DNS and DHCP servers. Or indeed the opposite you could decide to replace the three different hardware devices with a single server to reduce the administration overhead. In this case you can have three different addresses which are all on the same computer without having to install many physical network interfaces. Another reason to use IP aliasing could be to have the computer on two different logical network subnets whilst using a single physical interface.

## Related

- [[Application-layer framing]]
- [[Circuit-level gateway]]
- [[DIMES]]
- [[Echo (communications protocol)]]
- [[Fate-sharing]]
- [[Global network positioning]]
- [[Identifier-Locator Network Protocol]]
- [[Management plane]]
- [[Per-hop behaviour]]
- [[QPPB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IP_aliasing