---
title: "Fast and Secure Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_and_Secure_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Transport layer protocols"]
related: ["[[SCTP packet structure]]", "[[User Datagram Protocol]]", "[[Xpress Transport Protocol]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]"]
---

# Fast and Secure Protocol

The Fast Adaptive and Secure Protocol (FASP) is a proprietary data transfer protocol. FASP is a network-optimized network protocol created by Michelle C. Munson and Serban Simu, productized by Aspera, and now owned by IBM subsequent to its acquisition of Aspera. The associated client/server software packages are also commonly called Aspera. The technology is patented under US Patent #8085781, Bulk Data Transfer,  #20090063698, Method and system for aggregate bandwidth control. and others.
Built upon the connectionless UDP protocol, FASP does not expect any feedback on every packet sent, and yet provides fully reliable data transfer over best effort IP networks. Only the packets marked as really lost must be requested again by the recipient. As a result, it does not suffer as much loss of throughput as TCP does on networks with high latency or high packet loss and avoids the overhead of naive "UDP data blaster" protocols. The protocol innovates upon naive "data blaster" protocols through an optimal control-theoretic retransmission algorithm and implementation that achieves maximum goodput and avoids redundant retransmission of data. Its control model is designed to fill the available bandwidth of the end-to-end path over which the transfer occurs with only "good" and needed data.
Large organizations like the European Nucleotide Archive, the US National Institutes of Health National Center for Biotechnology Information and others use the protocol. The technology was recognized with many awards including an Engineering Emmy from the Academy of Film and Television.

## Related

- [[SCTP packet structure]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Fast_and_Secure_Protocol