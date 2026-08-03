---
title: "Stream X-Machine"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Stream_X-Machine"
wikipedia_categories: ["Models of computation", "Software testing", "Theory of computation"]
related: ["[[Communicating X-machine]]", "[[Description number]]", "[[Extended finite-state machine]]", "[[Markov algorithm]]", "[[State diagram]]", "[[Turing machine equivalents]]", "[[X-machine]]", "[[X-Machine Testing]]", "[[-dev-full]]", "[[A-B testing]]"]
---

# Stream X-Machine

The Stream X-machine (SXM) is a model of computation introduced by Gilbert Laycock in his 1993 PhD thesis, The Theory and Practice of Specification Based Software Testing.
Based on Samuel Eilenberg's X-machine, an extended finite-state machine for processing data of the type X,  the Stream X-Machine is a kind of X-machine for processing a memory data type Mem with associated input and output streams In* and Out*, that is, where X = Out* × Mem × In*.  The transitions of a Stream X-Machine are labelled by functions of the form φ: Mem × In → Out × Mem, that is, which compute an output value and update the memory, from the current memory and an input value.
Although the general X-machine had been identified in the 1980s as a potentially useful formal model for specifying software systems, it was not until the emergence of the Stream X-Machine that this idea could be fully exploited.  Florentin Ipate and Mike Holcombe went on to develop a theory of complete functional testing, in which complex software systems with hundreds of thousands of states and millions of transitions could be decomposed into separate SXMs that could be tested exhaustively, with a guaranteed proof of correct integration.
Because of the intuitive interpretation of Stream X-Machines as "processing agents with inputs and outputs", they have attracted increasing interest, because of their utility in modelling real-world phenomena.  The SXM model has important applications in fields as diverse as computational biology, software testing and agent-based computational economics.

## Related

- [[Communicating X-machine]]
- [[Description number]]
- [[Extended finite-state machine]]
- [[Markov algorithm]]
- [[State diagram]]
- [[Turing machine equivalents]]
- [[X-machine]]
- [[X-Machine Testing]]
- [[-dev-full]]
- [[A-B testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stream_X-Machine