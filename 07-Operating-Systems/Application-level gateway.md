---
title: "Application-level gateway"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Application-level_gateway"
wikipedia_categories: ["Computer network security", "Internet Protocol based network software", "Windows services"]
related: ["[[Bastion host]]", "[[Cisco Security Agent]]", "[[Fail2ban]]", "[[OSSEC]]", "[[PacketFence]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]"]
---

# Application-level gateway

An application-level gateway (ALG, also known as application-layer gateway, application gateway, application proxy, or application-level proxy) is a security component that augments a firewall or NAT employed in a mobile network. It allows customized NAT traversal filters to be plugged into the gateway to support address and port translation for certain application layer "control/data" protocols such as FTP, BitTorrent, SIP, RTSP, file transfer in IM applications. In order for these protocols to work through NAT or a firewall, either the application has to know about an address/port number combination that allows incoming packets, or the NAT has to monitor the control traffic and open up port mappings (firewall pinholes) dynamically as required. Legitimate application data can thus be passed through the security checks of the firewall or NAT that would have otherwise restricted the traffic for not meeting its limited filter criteria.

## Related

- [[Bastion host]]
- [[Cisco Security Agent]]
- [[Fail2ban]]
- [[OSSEC]]
- [[PacketFence]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Application-level_gateway