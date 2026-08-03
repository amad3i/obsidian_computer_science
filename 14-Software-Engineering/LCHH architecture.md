---
title: "LCHH architecture"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/LCHH_architecture"
wikipedia_categories: ["Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]"]
---

# LCHH architecture

The Loader–Content–Handler–Handler, or "LCHH", is a web programming architecture that is closely modeled after the HTTP request-response cycle and the 3-tier web structure.
As its name suggests, LCHH defines four key implementation components:

The Loader is an ID'ed DIV container that identifies a partial update region for later content injection;
The Content that contains both static information and interactive elements, also known as "Triggers";
Client-side Handlers that process various trigger events, such as button clicks;
Server-side Handlers that respond to Ajax requests that are sent by the client-side handlers. Server-side handlers typically perform database CRUD operations before piggy-backing the updated content into the aforementioned Loader.

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

- Wikipedia: https://en.wikipedia.org/wiki/LCHH_architecture