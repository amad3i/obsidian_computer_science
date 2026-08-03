---
title: "Server Message Block"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Server_Message_Block"
wikipedia_categories: ["Application layer protocols", "Inter-process communication", "Network file systems", "Network protocols", "Windows communication and services"]
related: ["[[List of products that support SMB]]", "[[Web Application Messaging Protocol]]", "[[Advanced Message Queuing Protocol]]", "[[Apple Filing Protocol]]", "[[Bonjour Sleep Proxy]]", "[[Client–server model]]", "[[Comparison of MQTT implementations]]", "[[Data Stream Interface]]", "[[Decentralized autonomous organization]]", "[[Discovery and Launch]]"]
---

# Server Message Block

Server Message Block (SMB) is a communication protocol used to share files, printers, serial ports, and miscellaneous communications between nodes on a network. On Windows, the SMB implementation consists of two vaguely named Windows services: "Server" (ID: LanmanServer) and "Workstation" (ID: LanmanWorkstation). It uses NTLM or Kerberos protocols for user authentication. It also provides an authenticated inter-process communication (IPC) mechanism.
SMB was originally developed in 1983 by Barry A. Feigenbaum at IBM to share access to files and printers across a network of systems running IBM PC DOS. In 1987, Microsoft and 3Com implemented SMB in LAN Manager for OS/2, at which time SMB used the NetBIOS service atop the NetBIOS Frames protocol as its underlying transport. Later, Microsoft implemented SMB in Windows NT 3.1 and has been updating it ever since, adapting it to work with newer underlying transports: TCP/IP and NetBT. SMB over QUIC was introduced in Windows Server 2022. 
In 1996, Microsoft published a version of SMB 1.0 with minor modifications under the Common Internet File System (CIFS ) moniker. CIFS was compatible with even the earliest incarnation of SMB, including LAN Manager's. It supports symbolic links, hard links, and larger file size, but none of the features of SMB 2.0 and later. Microsoft's proposal, however, remained an Internet Draft and never achieved standard status. Microsoft has since discontinued the CIFS moniker but continues developing SMB and publishing subsequent specifications. Samba is a free software reimplementation of the SMB protocol and the Microsoft extensions to it.

## Related

- [[List of products that support SMB]]
- [[Web Application Messaging Protocol]]
- [[Advanced Message Queuing Protocol]]
- [[Apple Filing Protocol]]
- [[Bonjour Sleep Proxy]]
- [[Client–server model]]
- [[Comparison of MQTT implementations]]
- [[Data Stream Interface]]
- [[Decentralized autonomous organization]]
- [[Discovery and Launch]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Server_Message_Block