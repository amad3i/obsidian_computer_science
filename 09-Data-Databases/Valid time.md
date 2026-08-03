---
title: "Valid time"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Valid_time"
wikipedia_categories: ["Computer programming stubs", "Database management systems"]
related: ["[[Transaction time]]", "[[ACID]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[Association (object-oriented programming)]]", "[[Astronomical Data Query Language]]"]
---

# Valid time

In temporal databases, valid-time is the time period when an event happened or something was true in the real world, or more formally when a fact was valid in the modeled reality.
The valid-time period is an interval based on event times, which are referred to as event datetime in data vault. Other names are application-time period or real-world timeline. SQL:2011 supports valid time through so-called application time-period tables. In a database table, valid-time is often represented by two extra table-columns, such as start_validtime and end_validtime. The time interval is closed at its lower bound (denoted by [) and open at its upper bound (denoted by )).
In integration layers (for example a data warehouse), the valid time is controlled by the source system which delivers data to the data warehouse. For many reasons, the valid timeline is different from the transaction timeline (which is when data arrives in the warehouse), and it is important that the data warehouse is capable of unambiguously reporting what actually happened in the past by combining these two timelines. In bitemporal data models, valid time and transaction time can be represented two-dimensionally in a Cartesian coordinate system. When data are delivered from the integration layer and is to be represented in a presentation layer (often in a dimensional model or wide table) it is often desirable to have the data on only one timeline.

## Related

- [[Transaction time]]
- [[ACID]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[Association (object-oriented programming)]]
- [[Astronomical Data Query Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Valid_time