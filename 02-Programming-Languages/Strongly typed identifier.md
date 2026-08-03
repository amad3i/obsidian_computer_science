---
title: "Strongly typed identifier"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Strongly_typed_identifier"
wikipedia_categories: ["Data types", "Software design patterns"]
related: ["[[4D vector]]", "[[Abstract data type]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Address constant]]", "[[Aggregate pattern]]", "[[Algebraic data type]]"]
---

# Strongly typed identifier

A strongly typed identifier is user-defined data type which serves as an identifier or key that is strongly typed. This is a solution to the "primitive obsession" code smell as mentioned by Martin Fowler. The data type should preferably be immutable if possible. It is common for implementations to handle equality testing, serialization and model binding.
The strongly typed identifier commonly wraps the data type used as the primary key in the database, such as a string, an integer or universally unique identifier (UUID).
Web frameworks can often be configured to model bind properties on view models that are strongly typed identifiers. Object–relational mappers can often be configured with value converters to map data between the properties on a model using strongly typed identifier data types and database columns.

## Related

- [[4D vector]]
- [[Abstract data type]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Address constant]]
- [[Aggregate pattern]]
- [[Algebraic data type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Strongly_typed_identifier