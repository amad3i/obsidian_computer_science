---
title: "Skyline operator"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Skyline_operator"
wikipedia_categories: ["Data management", "Database software stubs", "Query languages", "Relational database management systems", "SQL"]
related: ["[[SQL]]", "[[SQL syntax]]", "[[SQLf]]", "[[Alpha (programming language)]]", "[[Apache Kylin]]", "[[Commit (data management)]]", "[[Data Analysis Expressions]]", "[[Data hub]]", "[[FrontBase]]", "[[HSQLDB]]"]
---

# Skyline operator

The skyline operator is the subject of an optimization problem and computes the Pareto optimum on tuples with multiple dimensions.
This operator is an extension to SQL proposed by Börzsönyi et al. to filter results from a database to keep only those objects that are not dominated by any other point on all dimensions.
The name skyline comes from the view on Manhattan from the Hudson River, where those buildings can be seen that are not hidden by any other. A building is visible if it is not dominated by a building that is taller or closer to the river (two dimensions, distance to the river minimized, height maximized).
Another application of the skyline operator involves selecting a hotel for a holiday. The user wants the hotel to be both cheap and close to the beach. However, hotels that are close to the beach may also be expensive. In this case, the skyline operator would only present those hotels that are not worse than any other hotel in both price and distance to the beach.

## Related

- [[SQL]]
- [[SQL syntax]]
- [[SQLf]]
- [[Alpha (programming language)]]
- [[Apache Kylin]]
- [[Commit (data management)]]
- [[Data Analysis Expressions]]
- [[Data hub]]
- [[FrontBase]]
- [[HSQLDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Skyline_operator