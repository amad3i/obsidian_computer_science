---
title: "Chunked transfer encoding"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Chunked_transfer_encoding"
wikipedia_categories: ["Data management", "Hypertext Transfer Protocol headers"]
related: ["[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]", "[[Association rule learning]]", "[[Astroinformatics]]"]
---

# Chunked transfer encoding

Chunked transfer encoding is a streaming data transfer mechanism available in Hypertext Transfer Protocol (HTTP) version 1.1, defined in RFC 9112 §7.1. In chunked transfer encoding, the data stream is divided into a series of non-overlapping "chunks". The chunks are sent out and received independently of one another. At any given time, no knowledge of the data stream outside the currently-being-processed chunk is necessary for either the sender or the receiver.
Each chunk is preceded by its size in bytes and transmission ends when a zero-length chunk is received. The chunked keyword in the Transfer-Encoding header is used to indicate chunked transfer. 
Chunked transfer encoding is not supported in HTTP/2, which provides its own mechanisms for data streaming.

## Related

- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]
- [[Association rule learning]]
- [[Astroinformatics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chunked_transfer_encoding