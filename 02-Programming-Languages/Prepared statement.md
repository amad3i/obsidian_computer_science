---
title: "Prepared statement"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Prepared_statement"
wikipedia_categories: ["Databases", "SQL"]
related: ["[[Foreign key]]", "[[User-defined function]]", "[[Alpha (programming language)]]", "[[Altibase]]", "[[Apache Drill]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]"]
---

# Prepared statement

In database management systems (DBMS), a prepared statement, parameterized statement, (not to be confused with parameterized query) is a feature where the database pre-compiles SQL code and stores the results, separating it from data. Benefits of prepared statements are:

efficiency, because they can be used repeatedly without re-compiling
security, by reducing or eliminating SQL injection attacks
A prepared statement takes the form of a pre-compiled template into which constant values are substituted during each execution, and typically use SQL DML statements such as INSERT, SELECT, or UPDATE.
A common workflow for prepared statements is:

Prepare: The application creates the statement template and sends it to the DBMS. Certain values are left unspecified, called parameters, placeholders or bind variables (labelled "?" below):
INSERT INTO products (name, price) VALUES (?, ?);
Compile: The DBMS compiles (parses, optimizes and translates) the statement template, and stores the result without executing it.
Execute: The application supplies (or binds) values for the parameters of the statement template, and the DBMS executes the statement (possibly returning a result). The application may request the DBMS to execute the statement many times with different values. In the above example, the application might supply the values "bike" for the first parameter and "10900" for the second parameter, and then later the values "shoes" and "7400".
The alternative to a prepared statement is calling SQL directly from the application source code in a way that combines code and data. The direct equivalent to the above example is:

Not all optimization can be performed at the time the statement template is compiled, for two reasons: the best plan may depend on the specific values of the parameters, and the best plan may change as tables and indexes change over time.
On the other hand, if a query is executed only once, server-side prepared statements can be slower because of the additional round-trip to the server. Implementation limitations may also lead to performance penalties; for example, some versions of MySQL did not cache results of prepared queries. 
A stored procedure, which is also precompiled and stored on the server for later execution, has similar advantages. Unlike a stored procedure, a prepared statement is not normally written in a procedural language and cannot use or modify variables or use control flow structures, relying instead on the declarative database query language. Due to their simplicity and client-side emulation, prepared statements are more portable across vendors.

## Related

- [[Foreign key]]
- [[User-defined function]]
- [[Alpha (programming language)]]
- [[Altibase]]
- [[Apache Drill]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Prepared_statement