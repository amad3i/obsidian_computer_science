---
title: "Simple Common Gateway Interface"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Simple_Common_Gateway_Interface"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Simple Common Gateway Interface

The Simple Common Gateway Interface (SCGI) is a protocol for applications to interface with HTTP servers, as an alternative to the CGI protocol. It is similar to FastCGI but is designed to be easier to parse. Unlike CGI, it permits a long-running service process to continue serving requests, thus avoiding delays in responding to requests due to setup overhead (such as connecting to a database).
SCGI is a protocol which defines communication between a web server and an application server. This is in contrast to CGI, which is an earlier application (gateway) interface designed to let the application programmer avoid the complexity of sockets and long-running service processes when poor scalability and high overhead are acceptable.
The SCGI protocol leverages the fact that the web server has already parsed and validated the HTTP request, and canonically communicates the request to the SCGI server while letting the application programmer avoid parsing ambiguities and protocol edge cases. This avoids the complicated header-parsing and header-combining rules from RFC 2616, saving significant complexity in the SCGI server process.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simple_Common_Gateway_Interface