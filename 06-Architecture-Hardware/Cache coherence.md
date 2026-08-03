---
title: "Cache coherence"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Cache_coherence"
wikipedia_categories: ["Cache coherency", "Concurrent computing", "Consistency models", "Parallel computing"]
related: ["[[Computer cluster]]", "[[History of computer clusters]]", "[[PelicanHPC]]", "[[Supercomputer]]", "[[Thread pool]]", "[[ABIT BP6]]", "[[Actor model]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]"]
---

# Cache coherence

In computer architecture, cache coherence is the uniformity of shared resource data that is stored in multiple local caches. In a cache coherent system, if multiple clients have a cached copy of the same region of a shared memory resource, all copies are the same. Without cache coherence, a change made to the region by one client may not be seen by others, and errors can result when the data used by different clients is mismatched.
A cache coherence protocol is used to maintain cache coherency. The two main types are snooping and directory-based protocols.
Cache coherence is of particular relevance in multiprocessing systems, where each CPU may have its own local cache of a shared memory resource.

## Related

- [[Computer cluster]]
- [[History of computer clusters]]
- [[PelicanHPC]]
- [[Supercomputer]]
- [[Thread pool]]
- [[ABIT BP6]]
- [[Actor model]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cache_coherence