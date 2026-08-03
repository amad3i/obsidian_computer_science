---
title: "Substitution failure is not an error"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Substitution_failure_is_not_an_error"
wikipedia_categories: ["C++", "Software design patterns"]
related: ["[[Curiously recurring template pattern]]", "[[Resource acquisition is initialization]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]"]
---

# Substitution failure is not an error

Substitution failure is not an error (SFINAE) is a principle in C++ where an invalid substitution of template parameters is not in itself an error.  David Vandevoorde first introduced the acronym SFINAE to describe related programming techniques.
Specifically, when creating a candidate set for overload resolution, some (or all) candidates of that set may be the result of instantiated templates with (potentially deduced) template arguments substituted for the corresponding template parameters. If an error occurs during the substitution of a set of arguments for any given template, the compiler removes the potential overload from the candidate set instead of stopping with a compilation error, provided that the C++ standard permits discarding such a substitution error as mentioned. If one or more candidates remain and overload resolution succeeds, the invocation is well-formed.
SFINAE is largely superseded by the addition of concepts in C++20, which allow for cleaner expressing of template type constraints.

## Related

- [[Curiously recurring template pattern]]
- [[Resource acquisition is initialization]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Substitution_failure_is_not_an_error