---
title: "Tuple space"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Tuple_space"
wikipedia_categories: ["Distributed computing architecture", "Java (software platform)", "Parallel computing", "Programming languages"]
related: ["[[Apache Storm]]", "[[Apache Samza]]", "[[Distributed memory]]", "[[Explicit multi-threading]]", "[[Futhark (programming language)]]", "[[Java (programming language)]]", "[[Julia (programming language)]]", "[[Kojo (learning environment)]]", "[[MapReduce]]", "[[Parallelization contract]]"]
---

# Tuple space

A tuple space is an implementation of the  associative memory paradigm for parallel/distributed computing. It provides a repository of tuples that can be accessed concurrently. As an illustrative example, consider that there are a group of processors that produce pieces of data and a group of processors that use the data. Producers post their data as tuples in the space, and the consumers then retrieve data from the space that match a certain pattern. This is also known as the blackboard metaphor. Tuple space may be thought as a form of distributed shared memory.
Tuple spaces were the theoretical underpinning of the Linda language developed by David Gelernter and Nicholas Carriero at Yale University in 1986.
Implementations of tuple spaces have also been developed for Java (JavaSpaces), Lisp, Lua, Prolog, Python, Ruby, Smalltalk, Tcl, and the .NET Framework.

## Related

- [[Apache Storm]]
- [[Apache Samza]]
- [[Distributed memory]]
- [[Explicit multi-threading]]
- [[Futhark (programming language)]]
- [[Java (programming language)]]
- [[Julia (programming language)]]
- [[Kojo (learning environment)]]
- [[MapReduce]]
- [[Parallelization contract]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tuple_space