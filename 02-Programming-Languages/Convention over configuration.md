---
title: "Convention over configuration"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Convention_over_configuration"
wikipedia_categories: ["Object-oriented programming", "Software design"]
related: ["[[Ambiguous viewpoint]]", "[[Entity–control–boundary]]", "[[Hexagonal architecture (software)]]", "[[Interface segregation principle]]", "[[Layer (object-oriented design)]]", "[[Object-oriented modeling]]", "[[Open–closed principle]]", "[[Package principles]]", "[[Responsibility-driven design]]", "[[SOLID]]"]
---

# Convention over configuration

Convention over configuration (also known as coding by convention) is a software design paradigm used by software frameworks that attempts to decrease the number of decisions that a developer using the framework is required to make without necessarily losing flexibility and don't repeat yourself (DRY) principles.
The concept was introduced by David Heinemeier Hansson to describe the philosophy of the Ruby on Rails web framework, but is related to earlier ideas like the concept of "sensible defaults" and the principle of least astonishment in user interface design.
The phrase essentially means a developer only needs to specify unconventional aspects of the application. For example, if there is a class Sales in the model, the corresponding table in the database is called "sales" by default. It is only if one deviates from this convention, such as  the table "product sales", that one needs to write code regarding these names.
When the convention implemented by the tool matches the desired behavior, it behaves as expected without having to write configuration files. Only when the desired behavior deviates from the implemented convention is explicit configuration required.
Ruby on Rails' use of the phrase is particularly focused on its default project file and directory structure, which prevent developers from having to write XML configuration files to specify which modules the framework should load, which was common in many earlier frameworks.

## Related

- [[Ambiguous viewpoint]]
- [[Entity–control–boundary]]
- [[Hexagonal architecture (software)]]
- [[Interface segregation principle]]
- [[Layer (object-oriented design)]]
- [[Object-oriented modeling]]
- [[Open–closed principle]]
- [[Package principles]]
- [[Responsibility-driven design]]
- [[SOLID]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Convention_over_configuration