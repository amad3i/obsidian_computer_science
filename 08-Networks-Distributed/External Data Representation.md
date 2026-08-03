---
title: "External Data Representation"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/External_Data_Representation"
wikipedia_categories: ["Data modeling languages", "Data serialization formats", "Data transmission", "Internet Standards", "Internet protocols", "Networking standards", "Sun Microsystems software"]
related: ["[[Type–length–value]]", "[[SDXF]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]"]
---

# External Data Representation

External Data Representation (XDR) is a technical standard format  for data serialization, for uses such as computer network protocols. It allows data to be transferred between different kinds of computer systems. Converting from the local representation to XDR is called encoding. Converting from XDR to the local representation is called decoding. XDR is implemented as a software library of functions which is portable between different operating systems and is also independent of the transport layer.
XDR uses a base unit of 4 bytes, 32 bits, serialized in big-endian order; smaller data types still occupy four bytes each after encoding. Variable-length types such as string and opaque are padded to a total divisible by four bytes. Floating-point numbers are represented in IEEE 754 format.

## Related

- [[Type–length–value]]
- [[SDXF]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/External_Data_Representation