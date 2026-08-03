---
title: "Presentation–abstraction–control"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Presentation–abstraction–control"
wikipedia_categories: ["Human–computer interaction", "Programming paradigms", "Software architecture", "Software design patterns", "User interfaces"]
related: ["[[Bulkhead pattern]]", "[[Command-line interface]]", "[[CSS framework]]", "[[Data, context and interaction]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Desktop metaphor]]", "[[DeviceKit]]", "[[ELMER guidelines]]", "[[Filter (software)]]"]
---

# Presentation–abstraction–control

Presentation–abstraction–control (PAC) is a software architectural pattern. It is an interaction-oriented software architecture, and is somewhat similar to model–view–controller (MVC) in that it separates an interactive system into three types of components responsible for specific aspects of the application's functionality. The abstraction component retrieves and processes the data, the presentation component formats the visual and audio presentation of data, and the control component handles things such as the flow of control and communication between the other two components.
In contrast to MVC, PAC is used as a hierarchical structure of agents, each consisting of a triad of presentation, abstraction and control parts. The agents (or triads) communicate with each other only through the control part of each triad. It also differs from MVC in that within each triad, it completely insulates the presentation (view in MVC) and the abstraction (model in MVC). This provides the option to separately multithread the model and view which can give the user experience of very short program start times, as the user interface (presentation) can be shown before the abstraction has fully initialized.

## Related

- [[Bulkhead pattern]]
- [[Command-line interface]]
- [[CSS framework]]
- [[Data, context and interaction]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Desktop metaphor]]
- [[DeviceKit]]
- [[ELMER guidelines]]
- [[Filter (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Presentation–abstraction–control