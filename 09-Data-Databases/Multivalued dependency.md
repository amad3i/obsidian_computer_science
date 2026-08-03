---
title: "Multivalued dependency"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Multivalued_dependency"
wikipedia_categories: ["Data modeling", "Database constraints"]
related: ["[[Database normalization]]", "[[Lossless join decomposition]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]", "[[Building information modeling]]", "[[BuildingSMART Data Dictionary]]", "[[Business rule management system]]"]
---

# Multivalued dependency

In database theory, a multivalued dependency is a full constraint between two sets of attributes in a relation.
In contrast to the functional dependency, the multivalued dependency requires that certain tuples be present in a relation. Therefore, a multivalued dependency is a special case of tuple-generating dependency. The multivalued dependency plays a role in the 4NF database normalization.
A multivalued dependency is a special case of a join dependency, with only two sets of values involved, i.e. it is a binary join dependency.
A multivalued dependency exists when there are at least three attributes (like X,Y and Z) in a relation and for a value of X there is a well defined set of values of Y and a well defined set of values of Z. However, the set of values of Y is independent of set Z and vice versa.

## Related

- [[Database normalization]]
- [[Lossless join decomposition]]
- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Bitemporal modeling]]
- [[Building information modeling]]
- [[BuildingSMART Data Dictionary]]
- [[Business rule management system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multivalued_dependency