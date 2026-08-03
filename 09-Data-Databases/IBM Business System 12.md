---
title: "IBM Business System 12"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/IBM_Business_System_12"
wikipedia_categories: ["1982 software", "IBM software", "Proprietary database management systems", "Query languages"]
related: ["[[IBM Db2]]", "[[Query by Example]]", "[[Rasdaman]]", "[[QL]]", "[[4th Dimension (software)]]", "[[Access query language]]", "[[Actian Vector]]", "[[Adaptive Server Enterprise]]", "[[Address constant]]", "[[Alpha (programming language)]]"]
---

# IBM Business System 12

Business System 12, or simply BS12, was one of the first fully relational database management systems, designed and implemented by IBM's Bureau Service subsidiary at the company's international development centre in Uithoorn, Netherlands.  Programming started in 1978 and the first version was delivered in 1982. It was never widely used and essentially disappeared soon after the division was shut down in 1985, possibly because IBM and other companies settled on SQL as the standard.
BS12's lasting contribution to history was the use of a new query language based on ISBL, created at IBM's UK Scientific Centre. Developers of the famous System R underway in the US at the same time were also consulted on certain matters concerning the engine, but the BS12 team rejected SQL unequivocally, being convinced that this apparently unsound and difficult-to-use language (which at that time was also relationally incomplete) would never catch on.
BS12 included a number of interesting features that have yet to appear on most SQL-based systems, some a consequence of following the ISBL precedent, others due to deliberate design. For instance, a view could be parameterised and parameters could be of type TABLE. Thus, a view could in effect be a new relational operator defined in terms of the existing operators.  Codd's DIVIDE operator was in fact implemented that way.
Another feature that could have easily been included in SQL systems was the support for update operations on the catalog tables (system tables describing the structure of the database, as in SQL).  A new table could be created by inserting a row into the TABLES catalog, and then columns added to it by inserting into COLUMNS.
In addition, BS12 was ahead of SQL in supporting user-defined functions and procedures, using a Turing complete sublanguage, triggers, and a simple "call" interface for use by application programs, all in its very first release in 1982.

## Related

- [[IBM Db2]]
- [[Query by Example]]
- [[Rasdaman]]
- [[QL]]
- [[4th Dimension (software)]]
- [[Access query language]]
- [[Actian Vector]]
- [[Adaptive Server Enterprise]]
- [[Address constant]]
- [[Alpha (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IBM_Business_System_12