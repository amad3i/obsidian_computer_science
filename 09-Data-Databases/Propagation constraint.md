---
title: "Propagation constraint"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Propagation_constraint"
wikipedia_categories: ["Computing stubs", "Relational database management systems"]
related: ["[[4th Dimension (software)]]", "[[Actian Vector]]", "[[Adaptive Server Enterprise]]", "[[Altibase]]", "[[Apache Calcite]]", "[[Apache Kylin]]", "[[Apache Phoenix]]", "[[ArcSDE]]", "[[Auditory display]]", "[[Automatic system recovery]]"]
---

# Propagation constraint

In database systems, a propagation constraint "details what should happen to a related table when we update a row or rows of a target table" (Paul Beynon-Davies, 2004, p.108). Tables are linked using primary key to foreign key relationships. It is possible for users to update one table in a relationship in such a way that the relationship is no longer consistent and this is known as breaking referential integrity. An example of breaking referential integrity: if a table of employees includes a department number for 'Housewares' which is a foreign key to a table of departments and a user deletes that department from the department table then Housewares employees records would refer to a non-existent department number. 
Propagation constraints are methods used by relational database management systems (RDBMS) to solve this problem by ensuring that relationships between tables are preserved without error. In his database textbook, Beynon-Davies explains the three ways that RDBMS handle deletions of target and related tuples:

Restricted Delete - the user cannot delete the target row until all rows that point to it (via foreign keys) have been deleted. This means that all Housewares employees would need to be deleted, or their departments changed, before removing the department from the departmental table.
Cascades Delete - can delete the target row and all rows that point to it (via foreign keys) are also deleted. The process is the same as a restricted delete, except that the RDBMS would delete the Houseware employees automatically before removing the department.
Nullifies Delete - can delete the target row and all foreign keys (pointing to it) are set to null. In this case, after removing the housewares department, employees who worked in this department would have a NULL (unknown) value for their department.

## Related

- [[4th Dimension (software)]]
- [[Actian Vector]]
- [[Adaptive Server Enterprise]]
- [[Altibase]]
- [[Apache Calcite]]
- [[Apache Kylin]]
- [[Apache Phoenix]]
- [[ArcSDE]]
- [[Auditory display]]
- [[Automatic system recovery]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Propagation_constraint