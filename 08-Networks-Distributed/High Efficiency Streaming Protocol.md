---
title: "High Efficiency Streaming Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/High_Efficiency_Streaming_Protocol"
wikipedia_categories: ["Hypertext Transfer Protocol", "Network protocols", "Streaming media systems"]
related: ["[[HTTP Live Streaming]]", "[[Dynamic Adaptive Streaming over HTTP]]", "[[HTTP tunnel]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]"]
---

# High Efficiency Streaming Protocol

== High Efficiency Streaming Protocol (HESP) ==
High Efficiency Streaming Protocol (also known as HESP) is an HTTP-based adaptive bitrate streaming protocol that enables high-quality streaming of media content over the Internet delivered from conventional HTTP web servers, such as HLS and DASH. The technology was developed by THEO Technologies and made available via the HESP Alliance, which has Synamedia and THEO Technologies as founding members. HESP brings sub-second latency and a fast channel change and is seen as a challenger of Low Latency HLS (LL-HLS, added to HLS standard in 2020) and Low Latency DASH (LL-DASH, added to DASH standard in 2019).

== Architecture ==
HTTP-based streaming protocols such as HLS and DASH typically use a segment-based approach. This means a video is cut up into TCP segments of a few seconds each, which requires video players to wait until the start of a new segment to start playback. This approach increases channel change times and introduces additional latency. HESP leverages a frame-based streaming approach, which does not require a trade-off between live latency and channel switching time.
When all components of the video workflow are optimized for low latency, HESP can provide for sub-second latency.
HESP requires implementation in the packager and player, and support for range requests and Chunked transfer encoding (CTE) in the CDN.

== Standardization ==
Work on HESP started in 2018; it became an IETF information draft in May 2021
The HESP Alliance, launched in 2020, promotes and catalyzes the adoption of HESP. It consists of streaming vendors and media companies, including Synamedia, THEO Technologies, G-Core, EZDRM, Mainstreaming, NativeWaves, and Hoki. The HESP Alliance technical working group is focused on further advancing the HESP standard.

== References ==

## Related

- [[HTTP Live Streaming]]
- [[Dynamic Adaptive Streaming over HTTP]]
- [[HTTP tunnel]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/High_Efficiency_Streaming_Protocol