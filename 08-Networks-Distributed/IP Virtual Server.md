---
title: "IP Virtual Server"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IP_Virtual_Server"
wikipedia_categories: ["High-availability cluster computing", "Internet Protocol based network software", "Parallel computing", "Routing", "Servers (computing)"]
related: ["[[OpenSSI]]", "[[AiScaler]]", "[[Anonymous remailer]]", "[[Ganglia (software)]]", "[[IBM Parallel Sysplex]]", "[[Linux Virtual Server]]", "[[Linux-HA]]", "[[MOSIX]]", "[[OpenHPC]]", "[[OpenMosix]]"]
---

# IP Virtual Server

IPVS (IP Virtual Server) implements transport-layer load balancing, usually called Layer 4 LAN switching, as part of the Linux kernel. It's configured via the user-space utility ipvsadm(8) tool.
IPVS is incorporated into the Linux Virtual Server (LVS), where it runs on a host and acts as a load balancer in front of a cluster of real servers.  IPVS can direct requests for TCP- and UDP-based services to the real servers, and make services of the real servers appear as virtual services on a single IP address.  IPVS is built on top of Netfilter.
IPVS is merged into versions 2.4.x and newer of the Linux kernel mainline.

## Related

- [[OpenSSI]]
- [[AiScaler]]
- [[Anonymous remailer]]
- [[Ganglia (software)]]
- [[IBM Parallel Sysplex]]
- [[Linux Virtual Server]]
- [[Linux-HA]]
- [[MOSIX]]
- [[OpenHPC]]
- [[OpenMosix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IP_Virtual_Server