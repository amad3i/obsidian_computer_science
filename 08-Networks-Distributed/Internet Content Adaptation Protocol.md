---
title: "Internet Content Adaptation Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Internet_Content_Adaptation_Protocol"
wikipedia_categories: ["Application layer protocols", "Internet protocols"]
related: ["[[Border Gateway Protocol]]", "[[DNS over HTTPS]]", "[[DNS over TLS]]", "[[Domain Name System]]", "[[GPSoverIP]]", "[[Internationalized Resource Identifier]]", "[[Internet Open Trading Protocol]]", "[[InterPlanetary File System]]", "[[Lightweight Directory Access Protocol]]", "[[Link-Local Multicast Name Resolution]]"]
---

# Internet Content Adaptation Protocol

The Internet Content Adaptation Protocol (ICAP) is a lightweight HTTP-like streaming RPC protocol specified in RFC 3507.  It is used to extend transparent proxy servers in a scalable way, thereby freeing up resources and standardizing the way in which new features are implemented. ICAP is generally used to implement virus scanning and content filters in transparent HTTP proxy caches.  It can also be used for language translation.  Content adaptation refers to performing the particular value added service (content manipulation) for the associated client request/response.
ICAP concentrates on leveraging edge-based devices (caching proxies) to help deliver value-added services. At the core of this process is a cache that will proxy all client transactions and will process them through  web servers. These ICAP servers are focused on a specific function, for example, ad insertion, virus scanning, multi-AV scanning, content translation, language translation, or content filtering. Off-loading value-added services from web servers to ICAP servers allows those same web servers to be scaled according to raw HTTP throughput versus having to handle these extra tasks.

## Related

- [[Border Gateway Protocol]]
- [[DNS over HTTPS]]
- [[DNS over TLS]]
- [[Domain Name System]]
- [[GPSoverIP]]
- [[Internationalized Resource Identifier]]
- [[Internet Open Trading Protocol]]
- [[InterPlanetary File System]]
- [[Lightweight Directory Access Protocol]]
- [[Link-Local Multicast Name Resolution]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Internet_Content_Adaptation_Protocol