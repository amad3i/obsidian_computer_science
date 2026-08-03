---
title: "JSP model 2 architecture"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/JSP_model_2_architecture"
wikipedia_categories: ["Software architecture", "Software design patterns"]
related: ["[[Bulkhead pattern]]", "[[Data, context and interaction]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Inversion of control]]", "[[JSP model 1 architecture]]", "[[Multitier architecture]]", "[[MVC4WPF]]", "[[Naked objects]]", "[[Presentation–abstraction–control]]"]
---

# JSP model 2 architecture

JSP Model 2 is a design pattern used in the design of Java Web applications which separates the display of content from the logic used to obtain and manipulate the content. Since Model 2 drives a separation between logic and display, it is usually associated with the model–view–controller (MVC) paradigm. While the exact form of the MVC "Model" was never specified by the Model 2 design, a number of publications recommend a formalized layer to contain MVC Model code. The Java BluePrints, for example, originally recommended using EJBs to encapsulate the MVC Model.
In a Model 2 application, requests from the client browser are passed to the controller. The controller performs any logic necessary to obtain the correct content for display. It then places the content in the request (commonly in the form of a JavaBean or POJO) and decides which view it will pass the request to. The view then renders the content passed by the controller.
Model 2 is recommended for medium- and large-sized applications.

## Related

- [[Bulkhead pattern]]
- [[Data, context and interaction]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Inversion of control]]
- [[JSP model 1 architecture]]
- [[Multitier architecture]]
- [[MVC4WPF]]
- [[Naked objects]]
- [[Presentation–abstraction–control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/JSP_model_2_architecture