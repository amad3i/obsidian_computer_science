---
title: "SCTP packet structure"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/SCTP_packet_structure"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Transport layer protocols"]
related: ["[[Fast and Secure Protocol]]", "[[User Datagram Protocol]]", "[[Xpress Transport Protocol]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]"]
---

# SCTP packet structure

The Stream Control Transmission Protocol (SCTP) has a simpler basic packet structure than TCP. Each consists of two basic sections:

The common header, which occupies the first 12 bytes. In the adjacent diagram, this header is highlighted in blue.
The data chunks, which form the remaining portion of the packet. In the diagram, the first chunk is highlighted in green and the last of N chunks (Chunk N) is highlighted in red. There are several types, including payload data and different control messages.

## Related

- [[Fast and Secure Protocol]]
- [[User Datagram Protocol]]
- [[Xpress Transport Protocol]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SCTP_packet_structure