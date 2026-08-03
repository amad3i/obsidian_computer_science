---
title: "JSP model 1 architecture"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/JSP_model_1_architecture"
wikipedia_categories: ["Software architecture", "Software design patterns"]
related: ["[[Bulkhead pattern]]", "[[Data, context and interaction]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Inversion of control]]", "[[JSP model 2 architecture]]", "[[Multitier architecture]]", "[[MVC4WPF]]", "[[Naked objects]]", "[[Presentation–abstraction–control]]"]
---

# JSP model 1 architecture

In the design of Java Web applications, there are two commonly used design models, referred to as Model 1 and Model 2.

In Model 1, a request is made to a JSP or servlet and then that JSP or servlet handles all responsibilities for the request, including processing the request, validating data, handling the business logic, and generating a response. The Model 1 architecture is commonly used in smaller, simple task applications due to its ease of development. 
Although conceptually simple, this architecture is not conducive to large-scale application development because, inevitably, a great deal of functionality is duplicated in each JSP. Also, the Model 1 architecture unnecessarily ties together the business logic and presentation logic of the application. Combining business logic with presentation logic makes it hard to introduce a new 'view' or access point in an application. For example, in addition to an HTML interface, you might want to include a Wireless Markup Language (WML) interface for wireless access. In this case, using Model 1 will unnecessarily require the duplication of the business logic with each instance of the presentation code.

## Related

- [[Bulkhead pattern]]
- [[Data, context and interaction]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Inversion of control]]
- [[JSP model 2 architecture]]
- [[Multitier architecture]]
- [[MVC4WPF]]
- [[Naked objects]]
- [[Presentation–abstraction–control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/JSP_model_1_architecture