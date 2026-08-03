---
title: "Tail latency"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Tail_latency"
wikipedia_categories: ["Artificial intelligence stubs", "Computer performance", "Distributed computing", "Quality of service", "Software engineering"]
related: ["[[Abstraction (computer science)]]", "[[ActivityPub]]", "[[Agent architecture]]", "[[Agile software development]]", "[[AI observability]]", "[[ALTQ]]", "[[Articulatory speech recognition]]", "[[Artificial intelligence in spirituality]]", "[[AT Protocol]]", "[[Attributional calculus]]"]
---

# Tail latency

Tail latency is a term used to describe the high-percentile response times seen in a system. This is usually measured at the 95th, 99th, or 99.9th percentile, not the average latency. In distributed systems, cloud computing, and large-scale web services, even a small number of slow requests can make the user experience and system performance much worse. Tail latency often happens because of things like resource contention, network variability, garbage collection pauses, and hardware heterogeneity.
A major problem in system design is managing tail latency, because lowering average latency doesn't always make the worst-case performance better. To lessen its effects, people often use techniques like request hedging, replication, load balancing, and adaptive timeouts. In latency-sensitive applications like search engines, financial systems, and real-time services, where service-level objectives (SLOs) are often based on high-percentile latencies, it is especially important to understand and improve tail latency.

## Related

- [[Abstraction (computer science)]]
- [[ActivityPub]]
- [[Agent architecture]]
- [[Agile software development]]
- [[AI observability]]
- [[ALTQ]]
- [[Articulatory speech recognition]]
- [[Artificial intelligence in spirituality]]
- [[AT Protocol]]
- [[Attributional calculus]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tail_latency