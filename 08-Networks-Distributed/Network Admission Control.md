---
title: "Network Admission Control"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Network_Admission_Control"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Network Admission Control

Network Admission Control (NAC) refers to Cisco's version of network access control, which restricts access to the network based on identity or security posture.  When a network device (switch, router, wireless access point, DHCP server, etc.) is configured for NAC, it can force user or machine authentication prior to granting access to the network.  In addition, guest access can be granted to a quarantine area for remediation of any problems that may have caused authentication failure.  This is enforced through an inline custom network device, changes to an existing switch or router, or a restricted DHCP class.  A typical (non-free) WiFi connection is a form of NAC.  The user must present some sort of credentials (or a credit card) before being granted access to the network.
In its initial phase, the Cisco Network Admission Control (NAC) functionality enables Cisco routers to enforce access privileges when an endpoint attempts to connect to a network. This access decision can be on the basis of information about the endpoint device, such as its current antivirus state. The antivirus state includes information such as version of antivirus software, virus definitions, and version of scan engine.
Network admission control systems allow noncompliant devices to be denied access, placed in a quarantined area, or given restricted access to computing resources, thus keeping insecure nodes from infecting the network.
The key component of the Cisco Network Admission Control program is the Cisco Trust Agent, which resides on an endpoint system and communicates with Cisco routers on the network. The Cisco Trust Agent collects security state information, such as what antivirus software is being used, and communicates this information to Cisco routers. The information is then relayed to a Cisco Secure Access Control Server (ACS) where access control decisions are made. The ACS directs the Cisco router to perform enforcement against the endpoint.
This Cisco product has been marked End of Life since November 30, 2011, which is Cisco's terminology for a product that is no longer developed or supported.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Network_Admission_Control