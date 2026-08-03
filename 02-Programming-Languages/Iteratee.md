---
title: "Iteratee"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Iteratee"
wikipedia_categories: ["Functional programming", "Iteration in programming"]
related: ["[[Catamorphism]]", "[[A-normal form]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Brute-force search]]", "[[Coinduction]]"]
---

# Iteratee

In functional programming, an iteratee is a composable abstraction for incrementally processing sequentially presented chunks of input data in a purely functional fashion. With iteratees, it is possible to lazily transform how a resource will emit data, for example, by converting each chunk of the input to uppercase as they are retrieved or by limiting the data to only the five first chunks without loading the whole input data into memory. Iteratees are also responsible for opening and closing resources, providing predictable resource management.
On each step, an iteratee is presented with one of three possible types of values: the next chunk of data, a value to indicate no data is available, or a value to indicate the iteration process has finished. It may return one of three possible types of values, to indicate to the caller what should be done next: one that means "stop" (and contains the final return value), one that means "continue" (and specifies how to continue), and one that means "signal an error". The latter types of values in effect represent the possible "states" of an iteratee. An iteratee would typically start in the "continue" state.
Iteratees are used in Haskell and Scala (in the Play Framework and in Scalaz), and are also available for F#. Various slightly different implementations of iteratees exist. For example, in the Play framework, they involve Futures so that asynchronous processing can be performed.
Because iteratees are called by other code which feeds them with data, they are an example of inversion of control. However, unlike many other examples of inversion of control such as SAX XML parsing, the iteratee retains a limited amount of control over the process. It cannot reverse back and look at previous data (unless it stores that data internally), but it can stop the process cleanly without throwing an exception (using exceptions as a means of control flow, rather than to signal an exceptional event, is often frowned upon by programmers).

## Related

- [[Catamorphism]]
- [[A-normal form]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Brute-force search]]
- [[Coinduction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iteratee