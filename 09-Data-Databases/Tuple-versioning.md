---
title: "Tuple-versioning"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Tuple-versioning"
wikipedia_categories: ["Computing stubs", "Data modeling"]
related: ["[[Structure of Management Information]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Auditory display]]", "[[Automatic system recovery]]", "[[Availability zone]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Biological computation]]", "[[Bitemporal modeling]]"]
---

# Tuple-versioning

Tuple-versioning (also called point-in-time) is a mechanism used in a relational database management system to store past states of a relation.  Normally, only the current state is captured.
Using tuple-versioning techniques, typically two values for time are stored along with each tuple: a start time and an end time.  These two values indicate the validity of the rest of the values in the tuple.
Typically when tuple-versioning techniques are used, the current tuple has a valid start time, but a null value for end time.  Therefore, it is easy and efficient to obtain the current values for all tuples by querying for the null end time.
A single query that searches for tuples with start time less than, and end time greater than, a given time (where null end time is treated as a value greater than the given time) will give as a result the valid tuples at the given time.
For example, if a person's job changes from Engineer to Manager, there would be two tuples in an Employee table, one with the value Engineer for job and the other with the value Manager for job.  The end time for the Engineer tuple would be equal to the start time for the Manager tuple.
The pattern known as log trigger uses this technique to automatically store historical information of a table in a database.

## Related

- [[Structure of Management Information]]
- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Auditory display]]
- [[Automatic system recovery]]
- [[Availability zone]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Biological computation]]
- [[Bitemporal modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tuple-versioning