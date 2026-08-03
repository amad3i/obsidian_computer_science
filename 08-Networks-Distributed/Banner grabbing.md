---
title: "Banner grabbing"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Banner_grabbing"
wikipedia_categories: ["Computer network security", "Computer security stubs"]
related: ["[[Cyber range]]", "[[Firewalk (computing)]]", "[[Honeytoken]]", "[[Operation Cyber Condition Zebra]]", "[[Safe@Office]]", "[[VPNBook]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]"]
---

# Banner grabbing

Banner grabbing is a technique used to gain information about a computer system on a network and the services running on its open ports. Administrators can use this to take inventory of the systems and services on their network. However, an intruder can use banner grabbing in order to find network hosts that are running versions of applications and operating systems with known exploits.
Some examples of service ports used for banner grabbing are those used by HTTP, FTP, and SMTP; ports 80, 21, and 587 respectively. Tools commonly used to perform banner grabbing are Telnet, Nmap and Netcat.
For example, one could establish a connection to a target web server using Netcat, then send an HTTP request. The response will typically contain information about the service running on the host:

This information may be used by an administrator to catalog this system, or by an intruder to narrow down a list of applicable exploits.
To prevent this, network administrators should restrict access to services on their networks and shut down unused or unnecessary services running on network hosts.
Shodan is a search engine for banners grabbed from port scanning the Internet.

## Related

- [[Cyber range]]
- [[Firewalk (computing)]]
- [[Honeytoken]]
- [[Operation Cyber Condition Zebra]]
- [[Safe@Office]]
- [[VPNBook]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Banner_grabbing