---
title: "Data, context and interaction"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Data,_context_and_interaction"
wikipedia_categories: ["Software architecture", "Software design patterns"]
related: ["[[Bulkhead pattern]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Inversion of control]]", "[[JSP model 1 architecture]]", "[[JSP model 2 architecture]]", "[[Multitier architecture]]", "[[MVC4WPF]]", "[[Naked objects]]", "[[Presentation–abstraction–control]]"]
---

# Data, context and interaction

Data, context, and interaction (DCI) is a paradigm used in computer software to program systems of communicating objects. Its goals are:

To improve the readability of object-oriented code by giving system behavior first-class status;
To cleanly separate code for rapidly changing system behavior (what a system does) versus slowly changing domain knowledge (what a system is), instead of combining both in one class interface;
To help software developers reason about system-level state and behavior instead of only object state and behavior;
To support an object style of thinking that is close to programmers' mental models, rather than the class style of thinking that overshadowed object thinking early in the history of object-oriented programming languages.
The paradigm separates the domain model (data) from use cases (context) and Roles that objects play (interaction). DCI is complementary to model–view–controller (MVC). MVC as a pattern language is still used to separate the data and its processing from presentation.

## Related

- [[Bulkhead pattern]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Inversion of control]]
- [[JSP model 1 architecture]]
- [[JSP model 2 architecture]]
- [[Multitier architecture]]
- [[MVC4WPF]]
- [[Naked objects]]
- [[Presentation–abstraction–control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data,_context_and_interaction