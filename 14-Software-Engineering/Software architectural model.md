---
title: "Software architectural model"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Software_architectural_model"
wikipedia_categories: ["Software architecture", "Software design patterns", "Software development"]
related: ["[[Bulkhead pattern]]", "[[Data, context and interaction]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Inversion of control]]", "[[JSP model 1 architecture]]", "[[JSP model 2 architecture]]", "[[Multitier architecture]]", "[[MVC4WPF]]", "[[Naked objects]]"]
---

# Software architectural model

An architectural model (in software) contains several diagrams representing static properties or dynamic (behavioral) properties of the software under design. The diagrams represent different viewpoints of the system at the appropriate scope of analysis. The diagrams are created by using available standards in which the primary aim is to illustrate a specific set of tradeoffs inherent in the structure and design of a system or ecosystem. Software architects utilize architectural models to facilitate communication and obtain peer feedback.
Some key elements in a software architectural model include:

Rich: For the viewpoint in question, there should be sufficient information to describe the area in detail. The information should not be lacking or vague. The goal is to minimize misunderstandings, not perpetuate them. See notes below on 'primary concern.'
Rigorous: The architect has applied a specific methodology to create this particular model, and the resulting model 'looks' a particular way. A test of rigorousness may state that if two architects, in different cities, were describing the same thing, the resulting diagrams would be nearly identical (with the possible exception of visual layout, to a point).
Diagram: In general, a model may refer to any abstraction that simplifies something for the sake of addressing a particular viewpoint. This definition specifically subclasses 'architectural models' to the subset of model descriptions that are represented as diagrams.
Standards: Standards work when everyone knows them and everyone uses them. This allows a level of communication that cannot be achieved when each diagram is substantially different from another.Unified Modeling Language(UML) is the most often quoted standard.
Primary Concern: It is easy to be too detailed by including many different needs in a single diagram. This should be avoided. It is better to draw multiple diagrams, one for each viewpoint, than to draw a 'mega diagram' that is extremely rich in content. Remember this: when building houses, the architect delivers many different diagrams. Each is used differently. Frequently the final package of plans will include diagrams with the floor plan many times: framing plan, electrical plan, heating plan, plumbing, etc. They ensure that the information provided is only what is needed. For example, a plumbing subcontractor does not need the details that an electrician would need to know.
Illustrate: The idea behind creating a model is to communicate and seek valuable feedback. The goal of the diagram should be to answer a specific question and to share that answer with others to:
see if they agree
guide their work.
Rule of thumb: know what it is you want to say, and whose work you intend to influence with it.
Specific Set of Tradeoffs: The architecture tradeoff analysis method (ATAM) methodology describes a process whereby software architecture can be peer-reviewed for appropriateness. ATAM does this by starting with a basic notion: there is no such thing as a design for all occasions. People can create a generic design, but then they need to alter it to specific situations based on the business requirements. In effect, people make tradeoffs. The diagram should make those specific tradeoffs visible. Therefore, before an architect creates a diagram, they should be prepared to describe, in words, which tradeoffs they are attempting to illustrate in this model.
Tradeoffs Inherent in the Structure and Design: A component is not a tradeoff. Tradeoffs rarely translate into an image on the diagram. Tradeoffs are the first principles that produce the design models. When an architect wishes to describe or defend a particular tradeoff, the diagram can be used to defend the position.
System or Ecosystem: Modeling in general can be done at different levels of abstraction. It is useful to model the architecture of a specific application, complete with components and interactions. It is also reasonable to model the systems of applications needed to deliver a complete business process (like order-to-cash). It is not commonly useful, however, to view the model of a single component and its classes as software architecture. At that level, the model, while valuable in its own right, illustrates design much more so than architecture.

## Related

- [[Bulkhead pattern]]
- [[Data, context and interaction]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Inversion of control]]
- [[JSP model 1 architecture]]
- [[JSP model 2 architecture]]
- [[Multitier architecture]]
- [[MVC4WPF]]
- [[Naked objects]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Software_architectural_model