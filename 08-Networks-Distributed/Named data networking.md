---
title: "Named data networking"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Named_data_networking"
wikipedia_categories: ["Computer networking", "Internet protocols", "Network layer protocols"]
related: ["[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Domain Name System]]", "[[Host model]]", "[[ICMPv6]]", "[[Identifier-Locator Network Protocol]]", "[[Internet Control Message Protocol]]", "[[Internet Group Management Protocol]]", "[[IPsec]]", "[[MacIP]]"]
---

# Named data networking

Named Data Networking (NDN) (related to content-centric networking (CCN), content-based networking, data-oriented networking or information-centric networking (ICN)) is a proposed Future Internet architecture that seeks to address problems in contemporary internet architectures like IP. NDN has its roots in an earlier project, Content-Centric Networking (CCN), which Van Jacobson first publicly presented in 2006. The NDN project is investigating Jacobson's proposed evolution from today's host-centric network architecture IP to a data-centric network architecture (NDN). The stated goal of this project is that with a conceptually simple shift, far-reaching implications for how people design, develop, deploy, and use networks and applications could be realized.
NDN has three core concepts that distinguish NDN from other network architectures. First, applications name data and data names will directly be used in network packet forwarding; consumer applications would request desired data by its name, so communications in NDN are consumer-driven. Second, NDN communications are secured in a data-centric manner wherein each piece of data (called a Data packet) will be cryptographically signed by its producer and sensitive payload or name components can also be encrypted for the purpose of privacy. In this way, consumers can verify the packet regardless of how the packet is fetched. Third, NDN adopts a stateful forwarding plane where forwarders will keep a state for each data request (called an Interest packet), and erase the state when a corresponding data packet comes back. NDN's stateful forwarding allows intelligent forwarding strategies, and eliminates loops.
Its premise is that the Internet is primarily used as an information distribution network, which is not a good match for IP, and that the future Internet's "thin waist" should be based on named data rather than numerically addressed hosts. The underlying principle is that a communication network should allow a user to focus on the data they need, named content, rather than having to reference a specific, physical location where that data is to be retrieved from, named hosts. The motivation for this is derived from the fact that the vast majority of current Internet usage (a "high 90% level of traffic") consists of data being disseminated from a source to a number of users. Named-data networking comes with potential for a wide range of benefits such as content caching to reduce congestion and improve delivery speed, simpler configuration of network devices, and building security into the network at the data level.

## Related

- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Domain Name System]]
- [[Host model]]
- [[ICMPv6]]
- [[Identifier-Locator Network Protocol]]
- [[Internet Control Message Protocol]]
- [[Internet Group Management Protocol]]
- [[IPsec]]
- [[MacIP]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Named_data_networking