---
title: "MAC-Forced Forwarding"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/MAC-Forced_Forwarding"
wikipedia_categories: ["Internet Standards", "Internet protocols"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]"]
---

# MAC-Forced Forwarding

MAC-Forced Forwarding (MACFF) is used to control unwanted broadcast traffic and host-to-host communication. This is achieved by directing network traffic from hosts located on the same subnet but at different locations to an upstream gateway device. This provides security at Layer 2 since no traffic is able to pass directly between the hosts.
MACFF is suitable for Ethernet networks where a layer 2 bridging device, known as an Ethernet Access Node (EAN), connects Access Routers to their clients. MACFF is configured on the EANs.
MACFF is described in RFC 4562, MAC-Forced Forwarding: A Method for Subscriber Separation on an Ethernet Access Network.
Allied Telesis switches implement MACFF using DHCP snooping to maintain a database of the hosts that appear on each switch port. When a host tries to access the network through a switch port, DHCP snooping checks the host’s IP address against the database to ensure that the host is valid.
MACFF then uses DHCP snooping to check whether the host has a gateway Access Router. If it does, MACFF uses a form of Proxy ARP to reply to any ARP requests, giving the router's MAC address. This forces the host to send all traffic to the router, even traffic destined to a host in the same subnet as the source. The router receives the traffic and makes forwarding decisions based on a set of forwarding rules, typically a QoS policy or a set of filters.

## Related

- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]
- [[Directory information tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MAC-Forced_Forwarding