---
title: "Interceptor pattern"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Interceptor_pattern"
wikipedia_categories: ["Architectural pattern (computer science)", "Concurrent computing", "Software design patterns"]
related: ["[[Data transfer object]]", "[[Action–domain–responder]]", "[[Active record pattern]]", "[[Concurrency pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Inversion of control]]"]
---

# Interceptor pattern

In the field of software development, an interceptor pattern is a software design pattern that is used when software systems or frameworks want to offer a way to change, or augment, their usual processing cycle. For example, a (simplified) typical processing sequence for a web-server is to receive a URI from the browser, map it to a file on disk, open the file and send its contents to the browser. Any of these steps could be replaced or changed, e.g. by replacing the way URIs are mapped to filenames, or by inserting a new step which processes the files contents.
Key aspects of the pattern are that the change is transparent and used automatically. In essence, the rest of the system does not have to know something has been added or changed and can keep working as before. To facilitate this, a predefined interface for extension has to be implemented, some kind of dispatching mechanism is required where interceptors are registered (this may be dynamic, at runtime, or static, e.g. through configuration files) and context objects are provided, which allow access to the framework's internal state.

## Related

- [[Data transfer object]]
- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Concurrency pattern]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Entity component system]]
- [[Front controller]]
- [[Identity map pattern]]
- [[Inversion of control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interceptor_pattern