---
title: "Cache pollution"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Cache_pollution"
wikipedia_categories: ["Cache (computing)", "Computer architecture", "Computer memory"]
related: ["[[Cache hierarchy]]", "[[Aperture (computer memory)]]", "[[Cache (computing)]]", "[[Computational RAM]]", "[[MCDRAM]]", "[[Memory ordering]]", "[[Random-access memory]]", "[[2025–present global memory supply shortage]]", "[[Abstraction layer]]", "[[Address space]]"]
---

# Cache pollution

Cache pollution describes situations where an executing computer program loads data into CPU cache unnecessarily, thus causing other useful data to be evicted from the cache into lower levels of the memory hierarchy, degrading performance. For example, in a multi-core processor, one core may replace the blocks fetched by other cores into shared cache, or prefetched blocks may replace demand-fetched blocks from the cache.

## Related

- [[Cache hierarchy]]
- [[Aperture (computer memory)]]
- [[Cache (computing)]]
- [[Computational RAM]]
- [[MCDRAM]]
- [[Memory ordering]]
- [[Random-access memory]]
- [[2025–present global memory supply shortage]]
- [[Abstraction layer]]
- [[Address space]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cache_pollution