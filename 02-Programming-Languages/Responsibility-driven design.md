---
title: "Responsibility-driven design"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Responsibility-driven_design"
wikipedia_categories: ["Object-oriented programming", "Software design"]
related: ["[[Ambiguous viewpoint]]", "[[Convention over configuration]]", "[[Entity–control–boundary]]", "[[Hexagonal architecture (software)]]", "[[Interface segregation principle]]", "[[Layer (object-oriented design)]]", "[[Object-oriented modeling]]", "[[Open–closed principle]]", "[[Package principles]]", "[[SOLID]]"]
---

# Responsibility-driven design

Responsibility-driven design is a design technique in object-oriented programming, which improves encapsulation by using the client–server model. It focuses on the contract by considering the actions that the object is responsible for and the information that the object shares. It was proposed by Rebecca Wirfs-Brock and Brian Wilkerson.
Responsibility-driven design is in direct contrast with data-driven design, which promotes defining the behavior of a class along with the data that it holds. Data-driven design is not the same as data-driven programming, which is concerned with using data to determine the control flow, not class design.
In the client–server model they refer to, both the client and the server are classes or instances of classes. At any particular time, either the client or the server represents an object. Both the parties commit to a contract and exchange information by adhering to it. The client can only make the requests specified in the contract and the server must answer these requests. Thus, responsibility-driven design tries to avoid dealing with details, such as the way in which requests are carried out, by instead only specifying the intent of a certain request. The benefit is increased encapsulation, since the specification of the exact way in which a request is carried out is private to the server.
To further the encapsulation of the server, Wirfs-Brock and Wilkerson call for language features that limit outside influence to the behavior of a class. They demand that the visibility of members and functions should be finely grained, such as in Eiffel programming language. Even finer control of the visibility of even classes is available in the Newspeak programming language.

## Related

- [[Ambiguous viewpoint]]
- [[Convention over configuration]]
- [[Entity–control–boundary]]
- [[Hexagonal architecture (software)]]
- [[Interface segregation principle]]
- [[Layer (object-oriented design)]]
- [[Object-oriented modeling]]
- [[Open–closed principle]]
- [[Package principles]]
- [[SOLID]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Responsibility-driven_design