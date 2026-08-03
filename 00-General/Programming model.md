---
title: "Programming model"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Programming_model"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Programming model

A programming model is an execution model coupled to an API or a particular pattern of code.  In this style, there are actually two execution models in play: the execution model of the base programming language and the execution model of the programming model.  An example is Spark where  Java is the base language, and Spark is the programming model.  Execution may be based on what appear to be library calls. Other examples include the POSIX Threads library and Hadoop's MapReduce. In both cases, the execution model of the programming model is different from that of the base language in which the code is written. For example, the C programming language has no behavior in its execution model for input/output or thread behavior. But such behavior can be invoked from C syntax, by making what appears to be a call to a normal C library.
What distinguishes a programming model from a normal library is that the behavior of the call cannot be understood in terms of the language the program is written in. For example, the behavior of calls to the POSIX thread library cannot be understood in terms of the C language. The reason is that the call invokes an execution model that is different from the execution model of the language. This invocation of an outside execution model is the defining characteristic of a programming model, in contrast to a programming language.
In parallel computing, the execution model often must expose features of the hardware in order to achieve high performance. The large amount of variation in parallel hardware causes a concurrent need for a similarly large number of parallel execution models. It is impractical to make a new language for each execution model, hence it is a common practice to invoke the behaviors of the parallel execution model via an API. So, most of the programming effort is done via parallel programming models rather than parallel languages. The terminology around such programming models tends to focus on the details of the hardware that inspired the execution model, and in that insular world the mistaken belief is formed that a programming model is only for the case when an execution model is closely matched to hardware features.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Programming_model