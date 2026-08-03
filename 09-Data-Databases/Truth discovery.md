---
title: "Truth discovery"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Truth_discovery"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]"]
---

# Truth discovery

Truth discovery (also known as truth finding) is the process of choosing the actual true value for a data item when different data sources provide conflicting information on it.
Several algorithms have been proposed to tackle this problem, ranging from simple methods like majority voting to more complex ones able to estimate the trustworthiness of data sources.
Truth discovery problems can be divided into two sub-classes: single-truth and multi-truth. In the first case only one true value is allowed for a data item (e.g birthday of a person, capital city of a country). While in the second case multiple true values are allowed (e.g. cast of a movie, authors of a book).
Typically, truth discovery is the last step of a data integration pipeline, when the schemas of different data sources have been unified and the records referring to the same data item have been detected.

## Related

- [[Altibase]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Truth_discovery