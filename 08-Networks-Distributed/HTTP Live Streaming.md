---
title: "HTTP Live Streaming"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/HTTP_Live_Streaming"
wikipedia_categories: ["Hypertext Transfer Protocol", "Multimedia", "Network protocols", "QuickTime", "Streaming media systems"]
related: ["[[Dynamic Adaptive Streaming over HTTP]]", "[[High Efficiency Streaming Protocol]]", "[[HTTP tunnel]]", "[[Protected Streaming]]", "[[Real-Time Messaging Protocol]]", "[[Reliable Internet Stream Transport]]", "[[Access Grid]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]"]
---

# HTTP Live Streaming

HTTP Live Streaming (also known as HLS) is an HTTP-based adaptive bitrate streaming communications protocol developed by Apple Inc. and released in 2009. Support for the protocol is widespread in media players, web browsers, mobile devices, and streaming media servers. As of 2022, an annual video industry survey has consistently found it to be the most popular streaming format.
HLS resembles MPEG-DASH in that it works by breaking the overall stream into a sequence of small HTTP-based file downloads, each downloading one short chunk of an overall potentially unbounded transport stream. A list of available streams, encoded at different bit rates, is sent to the client using an extended M3U playlist.
Based on standard HTTP transactions, HTTP Live Streaming can traverse any firewall or proxy server that lets through standard HTTP traffic, unlike UDP-based protocols such as RTP. This also allows content to be offered from conventional HTTP servers and delivered over widely available HTTP-based content delivery networks. The standard also includes a standard encryption mechanism and secure-key distribution using HTTPS, which together provide a simple DRM system. Later versions of the protocol also provide for trick-mode fast-forward and rewind and for integration of subtitles.
Apple has documented HTTP Live Streaming as an Internet Draft (Individual Submission), the first stage in the process of publishing it as a Request for Comments (RFC). As of December 2015, the authors of that document have requested the RFC Independent Stream Editor (ISE) to publish the document as an informational (non-standard) RFC outside of the IETF consensus process.
In August 2017, RFC 8216 was published to describe version 7 of the protocol.

## Related

- [[Dynamic Adaptive Streaming over HTTP]]
- [[High Efficiency Streaming Protocol]]
- [[HTTP tunnel]]
- [[Protected Streaming]]
- [[Real-Time Messaging Protocol]]
- [[Reliable Internet Stream Transport]]
- [[Access Grid]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HTTP_Live_Streaming