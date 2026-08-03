---
title: "Explicit multi-threading"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Explicit_multi-threading"
wikipedia_categories: ["Distributed computing architecture", "Parallel computing"]
related: ["[[Apache Samza]]", "[[Apache Storm]]", "[[Distributed memory]]", "[[MapReduce]]", "[[Parallelization contract]]", "[[RCUDA]]", "[[Supercomputer]]", "[[Tuple space]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]"]
---

# Explicit multi-threading

Explicit Multi-Threading  (XMT) is a computer science paradigm for building and programming parallel computers designed around the parallel random-access machine (PRAM) parallel computational model. A more direct explanation of XMT starts with the rudimentary abstraction that made serial computing simple: that any single instruction available for execution in a serial program executes immediately. A consequence of this abstraction is a step-by-step (inductive) explication of the instruction available next for execution. The rudimentary parallel abstraction behind XMT, dubbed Immediate Concurrent Execution (ICE) in Vishkin (2011), is that indefinitely many instructions available for concurrent execution execute immediately. A consequence of ICE is a step-by-step (inductive) explication of the instructions available next for concurrent execution. Moving beyond the serial von Neumann computer (the only successful general-purpose platform to date), the aspiration of XMT is that computer science will again be able to augment mathematical induction with a simple one-line computing abstraction.
The random-access machine (RAM) is an abstract machine model used in computer science to study algorithms and complexity for standard serial computing. The PRAM computational model is an abstract parallel machine model that had been introduced to similarly study parallel algorithms and complexity for parallel computing, when they were yet to be built. Researchers have developed a large body of knowledge of parallel algorithms for the PRAM model. These parallel algorithms are also known for being simple, by standards of other approaches to parallel algorithms.
This large body of parallel algorithms knowledge for the PRAM model and their relative simplicity motivated building computers whose programming can be guided by these parallel algorithms. Since productivity of parallel programmers has long been considered crucial for the success a parallel computer, simplicity of  algorithms is important.
Multi-core computers are built around two or more processor cores integrated on a single integrated circuit die. They are widely used across many application domains including general-purpose computing.
Explicit Multi-Threading (XMT) is a computing paradigm for building and programming multi-core computers with tens, hundreds or thousands of processor cores.
Experimental work published in 2011 and 2012 demonstrates significantly greater speedups for advanced PRAM algorithms on XMT prototypes than for the same problems on state-of-the-art multi-core computers.
Work published in 2018 shows that lock-step parallel programming (using ICE) can achieve the same performance as the fastest hand-tuned multi-threaded code on XMT systems. Such inductive lock-step approach stands in contrast to multi-threaded programming approaches of many other core systems that are known for challenging programmers.
The XMT paradigm was introduced by Uzi Vishkin.

## Related

- [[Apache Samza]]
- [[Apache Storm]]
- [[Distributed memory]]
- [[MapReduce]]
- [[Parallelization contract]]
- [[RCUDA]]
- [[Supercomputer]]
- [[Tuple space]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Explicit_multi-threading