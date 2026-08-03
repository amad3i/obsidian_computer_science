---
title: "SYN cookies"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/SYN_cookies"
wikipedia_categories: ["Computer network security", "Transmission Control Protocol"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# SYN cookies

SYN cookie is a technique used to resist SYN flood attacks. The technique's primary inventor Daniel J. Bernstein defines SYN cookies as "particular choices of initial TCP sequence numbers by TCP servers." In particular, the use of SYN cookies allows a server to avoid dropping connections when the SYN queue fills up. Instead of storing additional connections, a SYN queue entry is encoded into the sequence number sent in the SYN+ACK response. If the server then receives a subsequent ACK response from the client with the incremented sequence number, the server is able to reconstruct the SYN queue entry using information encoded in the TCP sequence number and proceed as usual with the connection.

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

- Wikipedia: https://en.wikipedia.org/wiki/SYN_cookies