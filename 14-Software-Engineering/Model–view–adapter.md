---
title: "Model–view–adapter"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Model–view–adapter"
wikipedia_categories: ["Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]"]
---

# Model–view–adapter

Model–view–adapter (MVA) or mediating-controller MVC is a software architectural pattern and multitier architecture. In complex computer applications that present large amounts of data to users, developers often wish to separate data (model) and user interface (view) concerns so that changes to the user interface will not affect data handling and that the data can be reorganized without changing the user interface. MVA and traditional MVC both attempt to solve this same problem, but with two different styles of solution. Traditional MVC arranges model (e.g., data structures and storage), view (e.g., user interface), and controller (e.g., business logic) in a triangle, with model, view, and controller as vertices, so that some information flows between the model and views outside of the controller's direct control. The model–view–adapter solves this rather differently from the model–view–controller by arranging model, adapter or mediating controller and view linearly without any connections whatsoever directly between model and view.

## Related

- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Entity component system]]
- [[Front controller]]
- [[Identity map pattern]]
- [[Interceptor pattern]]
- [[Inversion of control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Model–view–adapter