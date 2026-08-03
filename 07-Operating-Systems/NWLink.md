---
title: "NWLink"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/NWLink"
wikipedia_categories: ["Network protocols", "Windows communication and services"]
related: ["[[Bonjour Sleep Proxy]]", "[[Discovery and Launch]]", "[[Link Layer Topology Discovery]]", "[[List of products that support SMB]]", "[[Server Message Block]]", "[[Transport Driver Interface]]", "[[Windows Rally]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]"]
---

# NWLink

NWLink is Microsoft's implementation of Novell's IPX/SPX protocols. NWLink includes an implementation of NetBIOS atop IPX/SPX.
NWLink packages data to be compatible with client/server services on NetWare Networks.  However, NWLink does not provide access to NetWare File and Print Services. To access the File and Print Services the Client Service for NetWare needs to be installed.
NWLink connects NetWare servers through the Gateway Service for NetWare or Client Service for NetWare and provides the transport protocol that connects Windows operating systems to IPX/SPX NetWare networks and compatible operating systems. NWLink supports NetBIOS and Windows Sockets application programming interfaces (API).
NWLink protocols are as follows:

SPX/SPXII
IPX
Service Advertising Protocol (SAP)
Routing Information Protocol (RIP)
NetBIOS
Forwarder
NWLink also provides the following functionalities:

Runs other communication protocol stacks, such as Transmission Control Protocol/Internet Protocol (TCP/IP)
Uses multiple frame types for network adapter binding

## Related

- [[Bonjour Sleep Proxy]]
- [[Discovery and Launch]]
- [[Link Layer Topology Discovery]]
- [[List of products that support SMB]]
- [[Server Message Block]]
- [[Transport Driver Interface]]
- [[Windows Rally]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/NWLink