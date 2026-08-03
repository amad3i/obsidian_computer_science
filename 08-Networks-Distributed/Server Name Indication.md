---
title: "Server Name Indication"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Server_Name_Indication"
wikipedia_categories: ["Internet protocols", "Secure communication", "Transport Layer Security", "Web hosting"]
related: ["[[Automatic Certificate Management Environment]]", "[[DNS over TLS]]", "[[HTTPS]]", "[[OCSP stapling]]", "[[Online Certificate Status Protocol]]", "[[Application-Layer Protocol Negotiation]]", "[[Asynchronous Layered Coding]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]"]
---

# Server Name Indication

Server Name Indication (SNI) is an extension to Transport Layer Security (TLS) where a client indicates which hostname it is attempting to connect to at the start of the handshaking process. The extension allows a server to present one of multiple possible certificates on the same IP address and port number, allowing for multiple services (including HTTPS websites) to be served by the same IP address without using a single certificate. For HTTPS, it is the conceptual equivalent to HTTP/1.1 virtual hosting. In the original specification, the hostname is not encrypted; the later Encrypted Client Hello specification rectifies this. The SNI extension was specified in 2003 in RFC 3546.

## Related

- [[Automatic Certificate Management Environment]]
- [[DNS over TLS]]
- [[HTTPS]]
- [[OCSP stapling]]
- [[Online Certificate Status Protocol]]
- [[Application-Layer Protocol Negotiation]]
- [[Asynchronous Layered Coding]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Server_Name_Indication