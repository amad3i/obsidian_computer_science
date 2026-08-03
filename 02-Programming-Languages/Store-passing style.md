---
title: "Store-passing style"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Store-passing_style"
wikipedia_categories: ["Functional programming", "Software design patterns"]
related: ["[[Applicative functor]]", "[[Monad (functional programming)]]", "[[A-normal form]]", "[[Abstract factory pattern]]", "[[Actant]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]"]
---

# Store-passing style

Store-passing style is a programming technique that is used to model mutable state without using mutable state. It generally arises in the conversion of imperative programs into purely functional ones.
So, for instance, consider this JavaScript program, written in a non-store-passing-style:

This contains a reference to a global variable. In store-passing style, the value of the global variable (or variables) is passed along to each call, and also returned from each call and threaded through the next call. The code might look like this:

Note that each call takes an extra argument, and two values are now returned; the ordinary return value, and a new value representing the state of the formerly mutable variable.
Store-passing style can be quite painful to write, but can help to eliminate race conditions by isolating state within function calls, and can potentially make code more parallelizable.

## Related

- [[Applicative functor]]
- [[Monad (functional programming)]]
- [[A-normal form]]
- [[Abstract factory pattern]]
- [[Actant]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Store-passing_style