---
title: "DNSCrypt"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/DNSCrypt"
wikipedia_categories: ["Domain Name System", "Internet protocols"]
related: ["[[DNS over HTTPS]]", "[[DNS over TLS]]", "[[Domain Name System]]", "[[Forward-confirmed reverse DNS]]", "[[Link-Local Multicast Name Resolution]]", "[[List of DNS record types]]", "[[TSIG]]", "[[Anycast]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]"]
---

# DNSCrypt

DNSCrypt is a network protocol that authenticates and encrypts Domain Name System (DNS) traffic between the user's computer and recursive name servers.  DNSCrypt wraps unmodified DNS traffic between a client and a DNS resolver in a cryptographic construction, preventing eavesdropping and forgery by a man-in-the-middle.
It also mitigates UDP-based amplification attacks by requiring a question to be at least as large as the corresponding response. Thus, DNSCrypt helps to prevent DNS amplification attacks.
DNSCrypt was originally designed by Frank Denis and Yecheng Fu. Multiple free and open source software implementations exist. It is available for a variety of operating systems, including Unix, Apple iOS, Linux, Android, and Microsoft Windows. The free and open source software implementation dnscrypt-proxy  additionally integrates ODoH.

## Related

- [[DNS over HTTPS]]
- [[DNS over TLS]]
- [[Domain Name System]]
- [[Forward-confirmed reverse DNS]]
- [[Link-Local Multicast Name Resolution]]
- [[List of DNS record types]]
- [[TSIG]]
- [[Anycast]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DNSCrypt