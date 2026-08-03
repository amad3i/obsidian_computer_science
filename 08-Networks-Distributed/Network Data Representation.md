---
title: "Network Data Representation"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Network_Data_Representation"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Internet stubs", "Presentation layer protocols"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Endpoint Handlespace Redundancy Protocol]]", "[[SCVP]]", "[[Veronica (search engine)]]", "[[Asynchronous Layered Coding]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]"]
---

# Network Data Representation

Network Data Representation (NDR) is an implementation of the presentation layer in the OSI model. It is used for DCE/RPC and Microsoft RPC (MSRPC).
Network Data Representation (NDR) is a data encoding and decoding method used in  distributed systems, specifically in  Remote Procedure Call (RPC) systems. NDR is part of the Distributed Computing Environment (DCE) RPC, allowing different computers and systems to communicate by exchanging data in a standardized format. NDR facilitates data transfer between systems with different architectures, ensuring that data is correctly represented and understood on both ends.
The NDR format label specifies the integer representation (endianness) in its first 4 bits, the character representation (ASCII or EBCDIC) in its next 4 bits, and its floating-point representation (IEEE, VAX, Cray, or IBM floating-point) in its next 8 bits. The final 16 bits of the format label are reserved.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Endpoint Handlespace Redundancy Protocol]]
- [[SCVP]]
- [[Veronica (search engine)]]
- [[Asynchronous Layered Coding]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Network_Data_Representation