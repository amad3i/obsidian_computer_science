---
title: "HTTP ETag"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/HTTP_ETag"
wikipedia_categories: ["Cache (computing)", "Hypertext Transfer Protocol headers", "Internet privacy", "Proxy servers"]
related: ["[[Client Hints]]", "[[Do Not Track]]", "[[Flash proxy]]", "[[Global Privacy Control]]", "[[HTTP cookie]]", "[[Proxy server]]", "[[Third-party cookies]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]"]
---

# HTTP ETag

The ETag or entity tag is part of HTTP, the protocol for the World Wide Web. It is one of several mechanisms that HTTP provides for Web cache validation, which allows a client to make conditional requests. This mechanism allows caches to be more efficient and saves bandwidth, as a Web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control to help prevent simultaneous updates of a resource from overwriting each other.
An ETag is an opaque identifier assigned by a Web server to a specific version of a resource found at a URL. If the resource representation at that URL ever changes, a new and different ETag is assigned. Used in this manner, ETags are similar to fingerprints and can quickly be compared to determine whether two representations of a resource are the same.

## Related

- [[Client Hints]]
- [[Do Not Track]]
- [[Flash proxy]]
- [[Global Privacy Control]]
- [[HTTP cookie]]
- [[Proxy server]]
- [[Third-party cookies]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HTTP_ETag