---
title: "Multiple description coding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiple_description_coding"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Multiple description coding

Multiple description coding (MDC) in computing is a coding technique that fragments a single media stream into n substreams (n ≥ 2) referred to as descriptions. The packets of each description are routed over multiple, (partially) disjoint paths. In order to decode the media stream, any description can be used, however, the quality improves with the number of descriptions received in parallel. The idea of MDC is to provide error resilience to media streams. Since an arbitrary subset of descriptions can be used to decode the original stream, network congestion or packet loss — which are common in best-effort networks such as the Internet — will not interrupt the stream but only cause a (temporary) loss of quality. The quality of a stream can be expected to be roughly proportional to data rate sustained by the receiver.
MDC is a form of data partitioning, thus comparable to layered coding as it is used in MPEG-2 and MPEG-4. Yet, in contrast to MDC, layered coding mechanisms generate a base layer and n enhancement layers. The base layer is necessary for the media stream to be decoded, enhancement layers are applied to improve stream quality. However, the first enhancement layer depends on the base layer and each enhancement layer n + 1 depends on its subordinate layer n, thus can only be applied if n was already applied. Hence, media streams using the layered approach are interrupted whenever the base layer is missing and, as a consequence, the data of the respective enhancement layers is rendered useless. The same applies for missing enhancement layers. In general, this implies that in lossy networks the quality of a media stream is not proportional to the amount of correctly received data.
Besides increased fault tolerance, MDC allows for rate-adaptive streaming: Content providers send all descriptions of a stream without paying attention to the download limitations of clients. Receivers that cannot sustain the data rate only subscribe to a subset of these streams, thus freeing the content provider from sending additional streams at lower data rates.
The vast majority of state-of-the art codecs uses single description (SD) video coding. This approach does not partition any data at all. Despite the aforementioned advantages of MDC, SD codecs are still predominant. The reasons are probably the comparingly high complexity of codec development, the loss of some compression efficiency as well as the caused transmission overhead.
Though MDC has its practical roots in media communication, it is widely researched in the area of information theory.
A related technology is layered coding, which also produces multiple compressed streams, but with a hierarchy between these streams.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiple_description_coding