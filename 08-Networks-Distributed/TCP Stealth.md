---
title: "TCP Stealth"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/TCP_Stealth"
wikipedia_categories: ["Computer network security", "Computer network stubs", "TCP extensions"]
related: ["[[TCP Cookie Transactions]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[Firewall pinhole]]", "[[FTP bounce attack]]", "[[Interest Flooding Attack]]", "[[Miredo]]"]
---

# TCP Stealth

In computer networking, TCP Stealth is a proposed modification of the Transmission Control Protocol (TCP) to hide open ports of some TCP services from the public, in order to impede port scans. It is somewhat similar to the port knocking technique. As of May 2015 it is an IETF Internet Draft specification.
The proposal modifies the TCP three-way handshake by only accepting connections from clients that transmit a proof of knowledge of a shared secret. If the connection attempt does not use TCP Stealth, or if authentication fails, the server acts as if no service was listening on the port number.
The project and initial Internet Draft specification was announced on 15 August 2014, following the revelations about the GCHQ project HACIENDA, which uses port scanning to find vulnerable systems for Five Eyes intelligence agencies. The draft was written by researchers from the Technical University of Munich, Jacob Appelbaum of the Tor Project and Holger Kenn from Microsoft.

## Related

- [[TCP Cookie Transactions]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Authentication server]]
- [[Blacker (security)]]
- [[Egress filtering]]
- [[Firewall pinhole]]
- [[FTP bounce attack]]
- [[Interest Flooding Attack]]
- [[Miredo]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TCP_Stealth