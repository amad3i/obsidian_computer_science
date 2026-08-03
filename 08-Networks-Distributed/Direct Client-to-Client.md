---
title: "Direct Client-to-Client"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Direct_Client-to-Client"
wikipedia_categories: ["IRC", "Internet terminology", "Network protocols", "Protocols related to IRC"]
related: ["[[Inter-server]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Anonymous blog]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]"]
---

# Direct Client-to-Client

Direct Client-to-Client (DCC) (originally Direct Client Connection) is an IRC-related sub-protocol enabling peers to interconnect using an IRC server for handshaking in order to exchange files or perform non-relayed chats. Once established, a typical DCC session runs independently from the IRC server. Originally designed to be used with ircII it is now supported by many IRC clients. Some peer-to-peer clients on napster-protocol servers also have DCC send/get capability, including TekNap, SunshineUN and Lopster. A variation of the DCC protocol called SDCC (Secure Direct Client-to-Client), also known as DCC SCHAT supports encrypted connections. An RFC specification on the use of DCC does not exist.
DCC connections can be initiated in two different ways:

The most common way is to use CTCP to initiate a DCC session. The CTCP is sent from one user, over the IRC network, to another user.
Another way to initiate a DCC session is for the client to connect directly to the DCC server. Using this method, no traffic will go across the IRC network (the parties involved do not need to be connected to an IRC network in order to initiate the DCC connection).

## Related

- [[Inter-server]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Anonymous blog]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Direct_Client-to-Client