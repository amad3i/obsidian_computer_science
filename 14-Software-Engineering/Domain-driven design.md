---
title: "Domain-driven design"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Domain-driven_design"
wikipedia_categories: ["Software architecture", "Software design", "Software development philosophies"]
related: ["[[Event storming]]", "[[Function model]]", "[[Local-first software]]", "[[Model-driven application]]", "[[Multitier architecture]]", "[[Presentation logic]]", "[[Software design]]", "[[4+1 architectural view model]]", "[[Acceptance test-driven development]]", "[[Active reviews for intermediate designs]]"]
---

# Domain-driven design

Domain-driven design (DDD) is a software design approach that focuses on modeling software to match a domain according to input from that domain's experts. DDD is against the idea of having a single unified model; instead it divides a large system into bounded contexts, each of which have their own model.
Under domain-driven design, the structure and language of software code (class names, class methods, class variables) should match the business domain. For example: if software processes loan applications, it might have classes like "loan application", "customers", and methods such as "accept offer" and "withdraw".
Domain-driven design is predicated on the following goals:

placing the project's primary focus on the core domain and domain logic layer;
basing complex designs on a model of the domain;
initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems.
Critics of domain-driven design argue that developers must typically implement a great deal of isolation and encapsulation to maintain the model as a pure and helpful construct. While domain-driven design provides benefits such as maintainability, Microsoft recommends it only for complex domains where the model provides clear benefits in formulating a common understanding of the domain.
The term was coined by Eric Evans in his book of the same name published in 2003.

## Related

- [[Event storming]]
- [[Function model]]
- [[Local-first software]]
- [[Model-driven application]]
- [[Multitier architecture]]
- [[Presentation logic]]
- [[Software design]]
- [[4+1 architectural view model]]
- [[Acceptance test-driven development]]
- [[Active reviews for intermediate designs]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Domain-driven_design