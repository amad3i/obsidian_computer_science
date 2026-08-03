---
title: "Direct End to End Secure Chat Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Direct_End_to_End_Secure_Chat_Protocol"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Direct End to End Secure Chat Protocol

The Internet Assigned Numbers Authority (IANA) officially assigned port 4605 to the SixChat End2End Direct secure messaging protocol created by Sixscape Communications, Pte. Ltd. The assignment was issued by IANA on 11 September 2014.
There are a very limited number of port numbers, which are assigned by IANA for protocols recognized as viable, complying with current protocol design standards, and not already covered by existing Internet standards. For example, port 25 was assigned to the SMTP email protocol many years ago. This provides a standard port and reduces conflicts with other protocols. The technical review of the SixChat protocol was performed by Lars Eggert, the distinguished chair of the Internet Research Task Force.
The SixChat messaging protocol was created by Lawrence E. Hughes, co-founder and CTO of Sixscape Communications, for their SixChat Internet application software. The new protocol allows two SixChat User Agents to connect directly, perform mutual authentication with X.509 client digital certificates and then securely exchange a symmetric session key (for encryption of all content). SixChat uses the company’s Identity Registration Protocol (IANA assigned port 4604) for address registry and retrieval, as well as Public Key Infrastructure functions (to obtain and use client digital certificates).
End2End Direct messaging requires globally routable ("public") IP addresses for all nodes involved. It is incompatible with NAT (Network Address Translation). It can work within a private internet (a subset of the IPv4 Internet that uses a flat address space with no NAT), or between any two nodes on the public IPv6 Internet. NAT prevents incoming connections, so any user to user messaging must use intermediary servers.
End2End Direct Messaging has several advantages over indirect messaging via intermediary servers. End2End Direct traffic is highly decentralized, going only via the shortest network path between communicating parties. This makes it more difficult to intercept, monitor or block. Intermediary servers introduce reliability, salability and security issues. It is much easier to monitor or block network traffic that must go through a small number of "choke points".
It would be possible to use DNS for node name resolution (mapping node names to IP addresses) for End2End Direct messaging, but DNS is increasingly insecure, has no per-user authentication for registration or updating, and takes a long time to propagate. It has no good way to publish X.509 client digital certificates for users, and can only publish the address of a given network node, not the node most recently used by a particular person. IRP provides a highly secure address registry with per-user authentication (usually using X.509 certificate based Strong Client Authentication). Registered information is immediately available. IP addresses of highly mobile nodes (e.g. smart phones) may change frequently as the connect to different WiFi access points. This does not work well in the DNS model.
The SixChat End2End Messaging protocol is a streaming protocol (tcp based, connection oriented). It cannot be secured with TLS, which is an inherently Client/Server technology. It provides mutual strong authentication using only X.509 client digital certificates (no server cert involved), and symmetric session key exchange (via public/private key encryption or Ephemeral Diffie Hellman Key Exchange). This handshake is based on the design of TLS, but is not Client/Server, rather between peers. Unlike TLS, it lies entirely within the Application Layer the protocol messages are based on XML.
Nodes supporting End2End Direct messaging are neither client nor server, but must be able to originate and accept network connections (hence have characteristics of both clients and servers). Such a node is called a "User Agent".

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Direct_End_to_End_Secure_Chat_Protocol