---
title: "Data mesh"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_mesh"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]"]
---

# Data mesh

Data mesh is a sociotechnical approach to building a decentralized data architecture by leveraging a domain-oriented, self-serve design (in a software development perspective), and borrows Eric Evans’ theory of domain-driven design and Manuel Pais’ and Matthew Skelton’s theory of team topologies. Data mesh mainly concerns itself with the data itself, taking the data lake and the pipelines as a secondary concern.  The main proposition is scaling analytical data by domain-oriented decentralization. With data mesh, the responsibility for analytical data is shifted from the central data team to the domain teams, supported by a data platform team that provides a domain-agnostic data platform. This enables a decrease in data disorder or the existence of isolated data silos, due to the presence of a centralized system that ensures the consistent sharing of fundamental principles across various nodes within the data mesh and allows for the sharing of data across different areas.
In simpler words, data mesh is an architectural approach to data organization where instead of one centralized system the ownership of the data is given to the team that knows it best; eg the sales team knows the sales data best thus the sales data would only be used, created or published by the sales team. Thus each team share and manage its own separate data product separately instead of relying on one central data team. The organization provides common tools, governance and standards so other teams can easily access or use the required data.

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

- Wikipedia: https://en.wikipedia.org/wiki/Data_mesh