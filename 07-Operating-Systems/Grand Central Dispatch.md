---
title: "Grand Central Dispatch"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Grand_Central_Dispatch"
wikipedia_categories: ["MacOS", "Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Grand Central Dispatch

Grand Central Dispatch (GCD or libdispatch) is a technology developed by Apple Inc. to optimize application support for systems with multi-core processors and other symmetric multiprocessing systems. It is an implementation of task parallelism based on the thread pool pattern. The fundamental idea is to move the management of the thread pool out of the hands of the developer, and closer to the operating system. The developer injects "work packages" into the pool oblivious of the pool's architecture. This model improves simplicity, portability and performance.
GCD was first released with Mac OS X 10.6, and is also available with iOS 4 and above. The name "Grand Central Dispatch" is a reference to Grand Central Terminal.
The source code for the library that provides the implementation of GCD's services, libdispatch, was released by Apple under the Apache License on September 10, 2009.  It has been ported to FreeBSD 8.1+, MidnightBSD 0.3+, Linux, and Solaris. Attempts in 2011 to make libdispatch work on Windows were not merged into upstream. Apple has its own port of libdispatch.dll for Windows shipped with Safari and iTunes, but no SDK is provided.
Since around 2017, the original libdispatch repository hosted by Nick Hutchinson was deprecated in favor of a version that is part of the Swift core library created in June 2016. The new version supports more platforms, notably including Windows.

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

- Wikipedia: https://en.wikipedia.org/wiki/Grand_Central_Dispatch