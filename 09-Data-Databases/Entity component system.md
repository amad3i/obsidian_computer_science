---
title: "Entity component system"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Entity_component_system"
wikipedia_categories: ["Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]", "[[JavaBeans]]"]
---

# Entity component system

Entity component system (ECS) is a software architectural pattern. An ECS consists of entities composed of data components, along with systems that operate on those components. It is most associated with video game development for the representation of game world objects.
ECS prioritizes composition over inheritance. Every entity is defined not by a type hierarchy, but by the components associated with it. Systems act globally over all entities that have the required components. For example, a food system might iterate through every entity with a relevant component tracking hunger, and act on them to push them a little away from satiation at time intervals. Entities lacking the component like terrain or items would be naturally ignored by the food system.
Due to an ambiguity in the English language, an interpretation of the name is that an ECS is a system comprising entities and components. In the 2002 talk at GDC, Scott Bilas compared a C++ object system and his new custom component system. This is consistent with a traditional use of system terms in general systems engineering with Common Lisp Object System and type system as examples.
Although mostly found in video game development, the ECS can be useful in other domains, such as in robotics simulators like Gazebo.

## Related

- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Front controller]]
- [[Identity map pattern]]
- [[Interceptor pattern]]
- [[Inversion of control]]
- [[JavaBeans]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Entity_component_system