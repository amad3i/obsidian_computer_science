---
title: "Model–view–viewmodel"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Model–view–viewmodel"
wikipedia_categories: [".NET terminology", "Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]"]
---

# Model–view–viewmodel

Model–view–viewmodel (MVVM) is a layer architecture design in computer software that facilitates the separation of the development of a graphical user interface (GUI; the view)—be it via a markup language or GUI code—from the development of the business logic or back-end logic (the model) such that the view is not dependent upon any specific model platform.
The viewmodel of MVVM is a value converter, meaning it is responsible for exposing (converting) the data objects from the model in such a way they can be easily managed and presented. In this respect, the viewmodel is more model than view, and handles most (if not all) of the view's display logic. The viewmodel may implement a mediator pattern, organizing access to the back-end logic around the set of use cases supported by the view.
MVVM is a variation of Martin Fowler's Presentation Model design pattern. MVVM is very similar to the Model-view-presenter pattern.  It was invented by Microsoft architects Ken Cooper and Ted Peters specifically to simplify event-driven programming of user interfaces. The pattern was incorporated into the Windows Presentation Foundation (WPF) (Microsoft's .NET graphics system) and Silverlight, WPF's Internet application derivative. John Gossman, a Microsoft WPF and Silverlight architect, announced MVVM on his blog in 2005.
Model–view–viewmodel is also referred to as model–view–binder, especially in implementations not involving the .NET platform. ZK, a web application framework written in Java, and the JavaScript library KnockoutJS use model–view–binder.

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

- Wikipedia: https://en.wikipedia.org/wiki/Model–view–viewmodel