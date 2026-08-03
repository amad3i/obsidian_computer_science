---
title: "Portmap"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Portmap"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Remote procedure call", "Unix network-related software"]
related: ["[[Berkeley r-commands]]", "[[Finger (protocol)]]", "[[OFTP]]", "[[Rdate]]", "[[Rtelnet]]", "[[Telnet]]", "[[Wide Area Information Server]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]"]
---

# Portmap

The port mapper (rpc.portmap or just portmap, or rpcbind) is an Open Network Computing Remote Procedure Call (ONC RPC) service that runs on network nodes that provide other ONC RPC services.
Version 2 of the port mapper protocol maps ONC RPC program number/version number pairs to the network port number for that version of that program.  When an ONC RPC server is started, it will tell the port mapper, for each particular program number/version number pair it implements for a particular transport protocol (TCP or UDP), what port number it is using for that particular program number/version number pair on that transport protocol.  Clients wishing to make an ONC RPC call to a particular version of a particular ONC RPC service must first contact the port mapper on the server machine to determine the actual TCP or UDP port to use.
Versions 3 and 4 of the protocol, called the rpcbind protocol, map a program number/version number pair, and an indicator that specifies a transport protocol, to a transport-layer endpoint address for that program number/version number pair on that transport protocol.
The port mapper service always uses TCP or UDP port 111; a fixed port is required for it, as a client would not be able to get the port number for the port mapper service from the port mapper itself.
The port mapper must be started before any other RPC servers are started.
The port mapper service first appeared in SunOS 2.0.

## Related

- [[Berkeley r-commands]]
- [[Finger (protocol)]]
- [[OFTP]]
- [[Rdate]]
- [[Rtelnet]]
- [[Telnet]]
- [[Wide Area Information Server]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Portmap