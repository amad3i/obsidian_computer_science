---
title: "Multitier architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Multitier_architecture"
wikipedia_categories: ["Architectural pattern (computer science)", "Distributed computing architecture", "Software architecture", "Software design", "Software design patterns", "Software engineering terminology"]
related: ["[[Bulkhead pattern]]", "[[Inversion of control]]", "[[Presentation logic]]", "[[Publish–subscribe pattern]]", "[[Action–domain–responder]]", "[[Active record pattern]]", "[[Architecture astronaut]]", "[[Connection broker]]", "[[Data access object]]", "[[Data mapper pattern]]"]
---

# Multitier architecture

In software engineering, multitier architecture (often referred to as n-tier architecture or layered architecture) is a client–server architecture in which various levels of software architecture are physically separated. The most common use of multitier architecture is the three-tier architecture, which separates presentation, application processing and data management functions, such as in the case of Cisco's hierarchical internetworking model. Other tiers of separation may include the service layer, business layer, data access layer, and persistence layer.
N-tier application architecture provides a model by which developers can modify or add to a specific tier in the software development process instead of reworking the entire application. It is commonly used for small and simple applications because of its simplicity and low cost. In web development, three-tier architecture is often used to describe websites that comprise a front-end web server serving static content and some cached dynamic content, a middle dynamic content processing and generation application server, and a back-end database or data store.
In a strict layered system, each layer depends on the layer below it and can exist without the layers above it. In a relaxed layered system, a layer can also depend on all of the layers below it, creating additional couplings between layers. Some multitier architectures use a hybrid approach so that some layers are strict while other layers are relaxed. N-tier architecture may also be implemented with the model–view–presenter pattern.
The terms layer and tier are often used interchangeably, although layer is sometimes used to refer to a conceptual software logic structuring mechanism, while tier is used to refer to the physical hardware structuring mechanism for system infrastructure. In this usage, a three-layer solution could be deployed on a single tier, as in the case of an some database-centric architectures called RDBMS-only architecture or in personal workstations.

## Related

- [[Bulkhead pattern]]
- [[Inversion of control]]
- [[Presentation logic]]
- [[Publish–subscribe pattern]]
- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Architecture astronaut]]
- [[Connection broker]]
- [[Data access object]]
- [[Data mapper pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multitier_architecture