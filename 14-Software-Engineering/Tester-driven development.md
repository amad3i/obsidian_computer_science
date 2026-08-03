---
title: "Tester-driven development"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Tester-driven_development"
wikipedia_categories: ["Anti-patterns", "Software development process", "Software engineering stubs"]
related: ["[[Change control board]]", "[[Developer ecosystem]]", "[[ISO-IEC 33001]]", "[[Merise]]", "[[Microsoft Security Development Lifecycle]]", "[[Push on green]]", "[[Spike (software development)]]", "[[Active reviews for intermediate designs]]", "[[Adaptive algorithm]]", "[[Adaptive software development]]"]
---

# Tester-driven development

In software engineering, tester-driven development, or bug-driven development, is an anti-pattern where the requirements are determined by bug reports or test results rather than, for example, the value or cost of a feature. The concept is generally invoked facetiously, and comes with the implication that high volumes of computer code are written with little regard for unit testing by the programmers.
The term itself is a tongue-in-cheek reference to test-driven development, a widely used methodology in agile software practices. In test-driven development tests are used to drive the implementation towards fulfilling the requirements. Tester-driven development instead shortcuts the process by removing the determination of requirements and letting the testers (or the QA team) drive what they think the software should be through the testing (or QA) process.
Projects that are developed using this anti-pattern often suffer from being extremely late. Another common problem is poor code quality.
Common causes for projects ending up being run this way are often: 

The testing phase started too early;
Incomplete requirements;
Inexperienced testers;
Inexperienced developers;
Poor project management.
Things get worse when the testers realize that they don't know what the requirements are and therefore don't know how to test any particular code changes. The onus then falls on the developers of individual changes to write their own test cases and they are happy to do so because their own tests normally pass and their performance measurements improve. Project leaders are also delighted by the rapid reduction in the number of open change requests.

## Related

- [[Change control board]]
- [[Developer ecosystem]]
- [[ISO-IEC 33001]]
- [[Merise]]
- [[Microsoft Security Development Lifecycle]]
- [[Push on green]]
- [[Spike (software development)]]
- [[Active reviews for intermediate designs]]
- [[Adaptive algorithm]]
- [[Adaptive software development]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tester-driven_development