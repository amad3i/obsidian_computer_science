---
title: "File eXchange Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/File_eXchange_Protocol"
wikipedia_categories: ["File Transfer Protocol", "Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# File eXchange Protocol

File eXchange Protocol (FXP or FXSP) is a method of data transfer which uses FTP to transfer data from one remote server to another (inter-server) without routing this data through the client's connection. Conventional FTP involves a single server and a single client; all data transmission is done between these two. In the FXP session, a client maintains a standard FTP connection to two servers, and can direct either server to connect to the other to initiate a data transfer. The advantage of using FXP over FTP is evident when a high-bandwidth server demands resources from another high-bandwidth server, but only a low-bandwidth client, such as a network administrator working away from location, has the authority to access the resources on both servers.

## Related

- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/File_eXchange_Protocol