---
title: "Virtual circuit"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Virtual_circuit"
wikipedia_categories: ["Communication circuits", "Network protocols", "Packets (information technology)", "Telephone services"]
related: ["[[Cell relay]]", "[[Encapsulation (networking)]]", "[[List of packet-switched networks]]", "[[Packet switching]]", "[[VoFR]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]"]
---

# Virtual circuit

A virtual circuit (VC) is a means of transporting data over a data network, based on packet switching and in which a connection is first established across the network between two endpoints. The network, rather than having a fixed data rate reservation per connection as in circuit switching, takes advantage of the statistical multiplexing on its transmission links, an intrinsic feature of packet switching. 
The 1978 X.25 standardization of virtual circuits imposes per-connection flow controls at all user-to-network and network-to-network interfaces. This permits participation in congestion control and reduces the likelihood of packet loss in a heavily loaded network. Some circuit protocols provide reliable communication service through the use of data retransmissions invoked by error detection and automatic repeat request (ARQ). 
Before a virtual circuit may be used, it must be established between network nodes in the call setup phase. Once established, a bit stream or byte stream may be exchanged between the nodes, providing abstraction from low-level division into protocol data units, and enabling higher-level protocols to operate transparently.
An alternative to virtual-circuit networks are datagram networks.

## Related

- [[Cell relay]]
- [[Encapsulation (networking)]]
- [[List of packet-switched networks]]
- [[Packet switching]]
- [[VoFR]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Virtual_circuit