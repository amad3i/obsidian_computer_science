---
title: "Cache stampede"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cache_stampede"
wikipedia_categories: ["Cache (computing)", "Computer optimization", "Engineering failures", "Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Cache stampede

A cache stampede is a type of cascading failure that can occur when massively parallel computing systems with caching mechanisms come under a very high load. This behaviour is sometimes also called dog-piling.
To understand how cache stampedes occur, consider a web server that uses memcached to cache rendered pages for some period of time, to ease system load. Under particularly high load to a single URL, the system remains responsive as long as the resource remains cached, with requests being handled by accessing the cached copy. This minimizes the expensive rendering operation.
Under low load, cache misses result in a single recalculation of the rendering operation. The system will continue as before, with the average load being kept very low because of the high cache hit rate.
However, under very heavy load, when the cached version of that page expires, there may be sufficient concurrency in the server farm that multiple threads of execution will all attempt to render the content of that page simultaneously. Systematically, none of the concurrent servers know that the others are doing the same rendering at the same time. If sufficiently high load is present, this may by itself be enough to bring about congestion collapse of the system via exhausting shared resources. Congestion collapse results in preventing the page from ever being completely re-rendered and re-cached, as every attempt to do so times out. Thus, cache stampede reduces the cache hit rate to zero and keeps the system continuously in congestion collapse as it attempts to regenerate the resource for as long as the load remains very heavy.
To give a concrete example, assume the page in consideration takes 3 seconds to render and we have a traffic of 10 requests per second. Then, when the cached page expires, we have 30 processes simultaneously recomputing the rendering of the page and updating the cache with the rendered page.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cache_stampede