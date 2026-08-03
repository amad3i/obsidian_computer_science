---
title: "Unit of work"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Unit_of_work"
wikipedia_categories: ["Software engineering"]
related: ["[[Abstraction (computer science)]]", "[[Agile software development]]", "[[AI observability]]", "[[Behavior tree]]", "[[Bookmark manager]]", "[[Breakpoint]]", "[[Brownout (software engineering)]]", "[[Certified software development professional]]", "[[Component-based software engineering]]", "[[Configuration management]]"]
---

# Unit of work

A unit of work is a behavioral pattern in software development. Martin Fowler has defined it as everything one does during a business transaction which can affect the database. When the unit of work is finished, it will provide everything that needs to be done to change the database as a result of the work.
A unit of work encapsulates one or more code repositories[de] and a list of actions to be performed which are necessary for the successful implementation of self-contained and consistent data change. A unit of work is also responsible for handling concurrency issues, and can be used for transactions and stability patterns.[de]

## Related

- [[Abstraction (computer science)]]
- [[Agile software development]]
- [[AI observability]]
- [[Behavior tree]]
- [[Bookmark manager]]
- [[Breakpoint]]
- [[Brownout (software engineering)]]
- [[Certified software development professional]]
- [[Component-based software engineering]]
- [[Configuration management]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unit_of_work