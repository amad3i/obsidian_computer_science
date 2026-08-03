---
title: "SQLSTATE"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/SQLSTATE"
wikipedia_categories: ["Relational database management systems", "SQL"]
related: ["[[FrontBase]]", "[[HSQLDB]]", "[[Nested SQL]]", "[[Skyline operator]]", "[[SQL]]", "[[SQL syntax]]", "[[SQLf]]", "[[SQream DB]]", "[[Table (database)]]", "[[4th Dimension (software)]]"]
---

# SQLSTATE

Programs calling a database that accords to the SQL standard receive an indication of the success or failure of the call. This return code - which is called SQLSTATE - consists of 5 bytes. They are divided into two parts: the first and second bytes contain a class and the following three a subclass. Each class belongs to one of four categories: "S" denotes "Success" (class 00), "W" denotes "Warning" (class 01), "N" denotes "No data" (class 02), and "X" denotes "Exception" (all other classes).

Real DBMSs are free to define additional values for SQLSTATE to handle those features that are beyond the standard. Such values must use one of the characters [I-Z] or [5-9] as the first byte of class (first byte of SQLSTATE) or subclass (third byte of SQLSTATE).
In addition to SQLSTATE the SQL command GET DIAGNOSTICS offers more details about the last executed SQL command.
In very early versions of the SQL standard the return code was called SQLCODE and used a different coding schema.
The following table lists the standard-conforming values - based on SQL:2011. The table's last column shows the part of the standard that defines the row. If it is empty, the definition originates from part 2 Foundation.

## Related

- [[FrontBase]]
- [[HSQLDB]]
- [[Nested SQL]]
- [[Skyline operator]]
- [[SQL]]
- [[SQL syntax]]
- [[SQLf]]
- [[SQream DB]]
- [[Table (database)]]
- [[4th Dimension (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SQLSTATE