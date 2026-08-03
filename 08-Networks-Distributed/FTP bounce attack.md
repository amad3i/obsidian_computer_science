---
title: "FTP bounce attack"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/FTP_bounce_attack"
wikipedia_categories: ["Computer network security", "Computer network stubs", "File Transfer Protocol"]
related: ["[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[Firewall pinhole]]", "[[Interest Flooding Attack]]", "[[Miredo]]", "[[NetStumbler]]", "[[Network Based Application Recognition]]"]
---

# FTP bounce attack

FTP bounce attack is an exploit of the FTP protocol whereby an attacker is able to use the PORT command to request access to ports indirectly through the use of the victim machine, which serves as a proxy for the request, similar to an Open mail relay using SMTP.
This technique can be used to port scan hosts discreetly, and to potentially bypass a network's access-control list to access specific ports that the attacker cannot access through a direct connection, for example with the nmap port scanner. 
Nearly all modern FTP server programs are configured by default to refuse PORT commands that would connect to any host but the originating host, thwarting FTP bounce attacks.

## Related

- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Egress filtering]]
- [[Firewall pinhole]]
- [[Interest Flooding Attack]]
- [[Miredo]]
- [[NetStumbler]]
- [[Network Based Application Recognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FTP_bounce_attack