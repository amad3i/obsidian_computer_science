---
title: "Active record pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Active_record_pattern"
wikipedia_categories: ["Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]", "[[JavaBeans]]"]
---

# Active record pattern

In software engineering, the active record pattern is an architectural pattern. It is found in software that stores in-memory object data in relational databases. It was named by Martin Fowler in his 2003 book Patterns of Enterprise Application Architecture. The interface of an object conforming to this pattern would include functions such as Insert, Update, and Delete, plus properties that correspond more or less directly to the columns in the underlying database table.
The Active Record pattern is a Data Access Layer that performs bidirectional transfer of data between a persistent data store (often a relational database) and an in-memory data representation (the domain layer). A database table or view is wrapped into a class. Thus, an object instance is tied to a single row in the table. After creation of an object, a new row is added to the table upon save. Any object loaded gets its information from the database. When an object is updated, the corresponding row in the table is also updated. The wrapper class implements accessor methods or properties for each column in the table or view.
This pattern is commonly used by object persistence tools and in object–relational mapping (ORM). Typically, foreign key relationships will be exposed as an object instance of the appropriate type via a property.

## Related

- [[Action–domain–responder]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Entity component system]]
- [[Front controller]]
- [[Identity map pattern]]
- [[Interceptor pattern]]
- [[Inversion of control]]
- [[JavaBeans]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Active_record_pattern