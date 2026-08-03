---
title: "Dynamic Adaptive Streaming over HTTP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_Adaptive_Streaming_over_HTTP"
wikipedia_categories: ["Hypertext Transfer Protocol", "MPEG", "Multimedia", "Network protocols"]
related: ["[[HTTP Live Streaming]]", "[[High Efficiency Streaming Protocol]]", "[[HTTP tunnel]]", "[[Protected Streaming]]", "[[Real-Time Messaging Protocol]]", "[[Reliable Internet Stream Transport]]", "[[Access Grid]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]"]
---

# Dynamic Adaptive Streaming over HTTP

Dynamic Adaptive Streaming over HTTP (DASH), also known as MPEG-DASH, is an adaptive bitrate streaming technique that enables high quality streaming of media content over the Internet delivered from conventional HTTP web servers.
Similar to Apple's HTTP Live Streaming (HLS) solution, MPEG-DASH works by breaking the content into a sequence of small segments, which are served over HTTP. Each segment contains a short interval of playback time of content that is potentially many hours in duration, such as a movie or the live broadcast of a sport event. The content is made available at a variety of different bit rates, i.e., alternative segments encoded at different bit rates covering aligned short intervals of playback time. While the content is being played back by an MPEG-DASH client, the client uses a bit rate adaptation (ABR) algorithm to automatically select the segment with the highest bit rate possible that can be downloaded in time for playback without causing stalls or re-buffering events in the playback. Thus, an MPEG-DASH client can seamlessly adapt to changing network conditions and provide high quality playback with few stalls or re-buffering events.
MPEG-DASH is the first adaptive bit-rate HTTP-based streaming solution that is an international standard. MPEG-DASH should not be confused with a transport protocol — the transport protocol that MPEG-DASH uses depends on which version of HTTP is used: TCP is the transport over which HTTP and HTTP/2 run, while HTTP/3 runs over QUIC (which in turn runs over UDP). MPEG-DASH uses existing HTTP web server infrastructure that is used for delivery of essentially all World Wide Web content. It allows devices like Internet-connected televisions, TV set-top boxes, desktop computers, smartphones, tablets, etc. to receive multimedia content (video, TV, radio, etc.) delivered via the Internet, coping with variable Internet receiving conditions. Standardizing an adaptive streaming solution is meant to provide confidence to the market that the solution can be adopted for universal deployment, compared to similar but more proprietary solutions like Smooth Streaming by Microsoft, or HDS by Adobe. Unlike HDS, or Smooth Streaming, DASH is codec-agnostic, which means it can use content encoded with any coding format, such as H.265, H.264, VP9, etc.

## Related

- [[HTTP Live Streaming]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_Adaptive_Streaming_over_HTTP