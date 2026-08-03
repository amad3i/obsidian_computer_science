---
title: "Thread pool"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Thread_pool"
wikipedia_categories: ["Concurrent computing", "Parallel computing", "Software design patterns", "Threads (computing)"]
related: ["[[Asynchronous method invocation]]", "[[Cache coherence]]", "[[Computer cluster]]", "[[Concurrency pattern]]", "[[Concurrent object-oriented programming]]", "[[Data transfer object]]", "[[History of computer clusters]]", "[[Interceptor pattern]]", "[[Map (parallel pattern)]]", "[[Micro-thread (multi-core)]]"]
---

# Thread pool

In computer programming, a thread pool is a software design pattern for achieving concurrency of execution in a computer program. Often also called a replicated workers or worker-crew model, a thread pool maintains multiple threads waiting for tasks to be allocated for concurrent execution by the supervising program. By maintaining a pool of threads, the model increases performance and avoids latency in execution due to frequent creation and destruction of threads for short-lived tasks. Another good property - the ability to limit system load, when we use fewer threads than available. The number of available threads is tuned to the computing resources available to the program, such as a parallel  task queue after completion of execution.

## Related

- [[Asynchronous method invocation]]
- [[Cache coherence]]
- [[Computer cluster]]
- [[Concurrency pattern]]
- [[Concurrent object-oriented programming]]
- [[Data transfer object]]
- [[History of computer clusters]]
- [[Interceptor pattern]]
- [[Map (parallel pattern)]]
- [[Micro-thread (multi-core)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Thread_pool