---
title: "DNS over TLS"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/DNS_over_TLS"
wikipedia_categories: ["Application layer protocols", "Domain Name System", "Internet protocols", "Internet security", "Transport Layer Security"]
related: ["[[DNS over HTTPS]]", "[[Domain Name System]]", "[[Link-Local Multicast Name Resolution]]", "[[Tor (network)]]", "[[Automatic Certificate Management Environment]]", "[[Border Gateway Protocol]]", "[[DNS hijacking]]", "[[DNSChanger]]", "[[DNSCrypt]]", "[[Forward-confirmed reverse DNS]]"]
---

# DNS over TLS

DNS over TLS (DoT) is a network security protocol for encrypting and wrapping Domain Name System (DNS) queries and answers via the Transport Layer Security (TLS) protocol. The goal of the method is to increase user privacy and security by preventing eavesdropping and manipulation of DNS data via man-in-the-middle attacks. The well-known port number for DoT is 853.
While DNS over TLS is applicable to any DNS transaction, it was first standardized for use between stub or forwarding resolvers and recursive resolvers, in RFC 7858 in May of 2016. Subsequent IETF efforts specify the use of DoT between recursive and authoritative servers ("Authoritative DNS over TLS" or "ADoT") and a related implementation between authoritative servers (Zone Transfer-over-TLS or "xfr-over-TLS").

## Related

- [[DNS over HTTPS]]
- [[Domain Name System]]
- [[Link-Local Multicast Name Resolution]]
- [[Tor (network)]]
- [[Automatic Certificate Management Environment]]
- [[Border Gateway Protocol]]
- [[DNS hijacking]]
- [[DNSChanger]]
- [[DNSCrypt]]
- [[Forward-confirmed reverse DNS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DNS_over_TLS