---
title: "OFTP"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/OFTP"
wikipedia_categories: ["Application layer protocols", "Clear text protocols", "Internet Standards", "Internet protocols", "Network file transfer protocols", "Network protocols", "Unix network-related software"]
related: ["[[GPSoverIP]]", "[[Rtelnet]]", "[[Domain Name System]]", "[[Network File System]]", "[[RADIUS]]", "[[Telnet]]", "[[TZSP]]", "[[Berkeley r-commands]]", "[[Border Gateway Protocol]]", "[[Finger (protocol)]]"]
---

# OFTP

The Odette File Transfer Protocol (OFTP) is a protocol created in 1986, used for Electronic Data Interchange (EDI) between two communications business partners. Its name comes from the Odette Organisation (the Organization for data exchange by teletransmission in Europe).
The ODETTE File Transfer Protocol (ODETTE-FTP) was defined in 1986 by working group four of the Organisation for Data Exchange by Tele-Transmission in Europe (ODETTE) to address the electronic data interchange (EDI) requirements of the European automotive industry. It was designed in the spirit of the Open System Interconnection (OSI) model utilising the Network Service provided by the CCITT X.25 recommendation.
OFTP 2 was written in 2007 by Data Interchange, as a specification for the secure transfer of business documents over the Internet, ISDN and X.25 networks. A description of OFTP 1.3 can be found in RFC 2204, whilst OFTP 2 is defined in RFC 5024.
OFTP 2 can work point-to-point or indirectly via a VAN (Value Added Network). A single OFTP 2 entity can make and receive calls, exchanging files in both directions. This means that OFTP 2 can work in a push or pull mode, as opposed to AS2, which can only work in a push mode.
OFTP 2 can encrypt and digitally sign message data, request signed receipts and also offers high levels of data compression. All of these services are available when using OFTP 2 over TCP/IP, X.25/ISDN or native X.25. When used over a TCP/IP network such as the Internet, additional session-level security is available by using OFTP 2 over Transport Layer Security (TLS).

## Related

- [[GPSoverIP]]
- [[Rtelnet]]
- [[Domain Name System]]
- [[Network File System]]
- [[RADIUS]]
- [[Telnet]]
- [[TZSP]]
- [[Berkeley r-commands]]
- [[Border Gateway Protocol]]
- [[Finger (protocol)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/OFTP