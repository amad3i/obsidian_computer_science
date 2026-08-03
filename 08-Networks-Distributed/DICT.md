---
title: "DICT"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/DICT"
wikipedia_categories: ["DICT clients", "Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# DICT

DICT is a dictionary network protocol created by the DICT Development Group in 1997, described by RFC 2229. Its goal is to surpass the Webster protocol to allow clients to access a variety of dictionaries via a uniform interface.
In section 3.2 of the DICT protocol RFC, queries and definitions are sent in clear-text, meaning that there is no encryption. Nevertheless, according to section 3.1 of the RFC, various forms of authentication (sans encryption) are supported, including Kerberos version 4.

The protocol consists of a few commands a server must recognize so a client can access the available data and lookup word definitions. DICT servers and clients use TCP port 2628 by default. Queries are captured in the following URL scheme:dict://<user>;<auth>@<host>:<port>/<c>:<word>:<database>:<strategy>:<n>

## Related

- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DICT