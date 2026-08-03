---
title: "TCP Cookie Transactions"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/TCP_Cookie_Transactions"
wikipedia_categories: ["Computer network security", "Computer network stubs", "TCP extensions"]
related: ["[[TCP Stealth]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Authentication server]]", "[[Blacker (security)]]", "[[Egress filtering]]", "[[Firewall pinhole]]", "[[FTP bounce attack]]", "[[Interest Flooding Attack]]", "[[Miredo]]"]
---

# TCP Cookie Transactions

TCP Cookie Transactions (TCPCT) is specified in RFC 6013 (historic status, formerly experimental) as an extension of Transmission Control Protocol (TCP) intended to secure it against denial-of-service attacks, such as resource exhaustion by SYN flooding and malicious connection termination by third parties. Unlike the original SYN cookies approach, TCPCT does not conflict with other TCP extensions, but requires TCPCT support in the client (initiator) as well as the server (responder) TCP stack.
The immediate reason for the TCPCT extension is deployment of the DNSSEC protocol. Prior to DNSSEC, DNS requests primarily used short UDP packets, but due to the size of DNSSEC exchanges, and shortcomings of IP fragmentation, UDP is less practical for DNSSEC. Thus DNSSEC-enabled requests create a large number of short-lived TCP connections.
TCPCT avoids resource exhaustion on server-side by not allocating any resources until the completion of the three-way handshake. Additionally, TCPCT allows the server to release memory immediately after the connection closes, while it persists in the TIME-WAIT state.
TCPCT support was partly merged into the Linux kernel in December 2009, but was removed in May 2013 because it was never fully implemented and had a performance cost.
TCPCT was deprecated in 2016 in favor of TCP Fast Open.  Status of the original RFC was changed to "historic".

## Related

- [[TCP Stealth]]
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

- Wikipedia: https://en.wikipedia.org/wiki/TCP_Cookie_Transactions