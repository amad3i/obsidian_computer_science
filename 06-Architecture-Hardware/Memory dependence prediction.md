---
title: "Memory dependence prediction"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Memory_dependence_prediction"
wikipedia_categories: ["Computer architecture"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Branch queue]]", "[[Bridging model]]"]
---

# Memory dependence prediction

Memory dependence prediction is a technique, employed by high-performance out-of-order execution microprocessors that execute memory access operations (loads and stores) out of program order, to predict true dependencies between loads and stores at instruction execution time. With the predicted dependence information, the processor can then decide to speculatively execute certain loads and stores out of order, while preventing other loads and stores from executing out-of-order (keeping them in-order). Later in the pipeline, memory disambiguation techniques are used to determine if the loads and stores were correctly executed and, if not, to recover.
By using the memory dependence predictor to keep most dependent loads and stores in order, the processor gains the benefits of aggressive out-of-order load/store execution but avoids many of the memory dependence violations that occur when loads and stores were incorrectly executed. This increases performance because it reduces the number of pipeline flushes that are required to recover from these memory dependence violations. See the memory disambiguation article for more information on memory dependencies, memory dependence violations, and recovery.
In general, memory dependence prediction predicts whether two memory operations are dependent, that is, if they interact by accessing the same memory location. Besides using store to load (RAW or true) memory dependence prediction for the out-of-order scheduling of loads and stores, other applications of memory dependence prediction have been proposed. See for example.
Memory dependence prediction is an optimization on top of memory dependency speculation. Sequential execution semantics imply that stores and loads appear to execute in the order specified by the program. However, as with out-of-order execution of other instructions, it may be possible to execute two memory operations in a different order from that implied by the program. This is possible when the two operations are independent. In memory dependence speculation a load may be allowed to execute before a store that precedes it. Speculation succeeds when the load is independent of the store, that is, when the two instructions access different memory locations. Speculation fails when the load is dependent upon the store, that is, when the two accesses overlap in memory. In the first, modern out-of-order designs, memory speculation was not used as its benefits were limited. Αs the scope of the out-of-order execution increased over few tens of instructions, naive memory dependence speculation was used. In naive memory dependence speculation, a load is allowed to bypass any preceding store. As with any form of speculation, it is important to weight the benefits of correct speculation against the penalty paid on incorrect speculation. As the scope of out-of-order execution increases further into several tens of instructions, the performance benefits of naive speculation decrease. To retain the benefits of aggressive memory dependence speculation while avoiding the costs of mispeculation several predictors have been proposed.
Selective memory dependence prediction stalls specific loads until it is certain that no violation may occur. It does not explicitly predict dependencies. This predictor may delay loads longer than necessary and hence result in suboptimal performance. In fact, in some cases it performs worse than naively speculating all loads as early as possible. This is because often its faster to mispeculate and recover than to wait for all preceding stores to execute. Exact memory dependence prediction was developed at the University of Wisconsin–Madison. Specifically, Dynamic Speculation and Synchronization delays loads only as long as it is necessary by predicting the exact store a load should wait for. This predictor predicts exact dependences (store and load pair). The synonym predictor groups together all dependences that share a common load or store instruction. The store sets predictor represents multiple potential dependences efficiently by grouping together all possible stores a load may depend upon. The store barrier predictor treats certain store instructions as barriers. That is, all subsequent load or store operations are not allowed to bypass the specific store. The store barrier predictor does not explicitly predict dependencies. This predictor may unnecessarily delay subsequent, yet independent loads. Memory dependence prediction has other applications beyond the scheduling of loads and stores. For example, speculative memory cloaking and speculative memory bypassing use memory dependence prediction to streamline the communication of values through memory.

## Related

- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Branch queue]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Memory_dependence_prediction