---
title: "Pipeline (Unix)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Pipeline_(Unix)"
wikipedia_categories: ["Inter-process communication", "Unix"]
related: ["[[STREAMS]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Advanced Message Queuing Protocol]]", "[[ARexx]]", "[[Asynchrony (computer programming)]]", "[[Blocking (computing)]]", "[[Client–server model]]", "[[CMS Pipelines]]", "[[Common Object Request Broker Architecture]]", "[[Component Object Model]]"]
---

# Pipeline (Unix)

In Unix-like computer operating systems, a pipeline is a mechanism for inter-process communication using message passing. A pipeline is a set of processes chained together by their standard streams, so that the output text of each process (stdout) is passed directly as input (stdin) to the next one. The second process is started as the first process is still executing, and they are executed concurrently.
The concept of pipelines was championed by Douglas McIlroy at Unix's ancestral home of Bell Labs, during the development of Unix, shaping its toolbox philosophy. It is named by analogy to a physical pipeline. A key feature of these pipelines is their "hiding of internals". This in turn allows for more clarity and simplicity in the system.
The pipes in the pipeline are anonymous pipes (as opposed to named pipes), where data written by one process is buffered by the operating system until it is read by the next process, and this uni-directional channel disappears when the processes are completed. The standard shell syntax for anonymous pipes is to list multiple commands, separated by vertical bars ("pipes" in common Unix verbiage).

## Related

- [[STREAMS]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Advanced Message Queuing Protocol]]
- [[ARexx]]
- [[Asynchrony (computer programming)]]
- [[Blocking (computing)]]
- [[Client–server model]]
- [[CMS Pipelines]]
- [[Common Object Request Broker Architecture]]
- [[Component Object Model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pipeline_(Unix)