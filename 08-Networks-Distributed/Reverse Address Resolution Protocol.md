---
title: "Reverse Address Resolution Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Reverse_Address_Resolution_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Link protocols"]
related: ["[[Neighbor Discovery Protocol]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]"]
---

# Reverse Address Resolution Protocol

The Reverse Address Resolution Protocol (RARP) is an obsolete computer communication protocol used by a client computer to request its Internet Protocol (IPv4) address from a computer network, when all it has available is its link-layer or hardware address, such as a MAC address. The client broadcasts the request and does not need prior knowledge of the network topology or the identities of servers capable of fulfilling its request.
RARP has been rendered obsolete by the Bootstrap Protocol (BOOTP) and the modern Dynamic Host Configuration Protocol (DHCP), which have much greater feature sets than RARP.
RARP requires one or more server hosts to maintain a database of mappings of link-layer addresses to their respective protocol addresses. MAC addresses need to be individually configured on the servers by an administrator. RARP is limited to serving only IP addresses.
Reverse ARP differs from the Inverse Address Resolution Protocol (InARP), which is designed to obtain the IP address associated with a local Frame Relay data link connection identifier. InARP is not used in Ethernet.

## Related

- [[Neighbor Discovery Protocol]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reverse_Address_Resolution_Protocol