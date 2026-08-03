---
title: "SPARK (programming language)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/SPARK_(programming_language)"
wikipedia_categories: ["Ada (programming language)", "Ada programming language family", "Algol programming language family", "Concurrent programming languages", "Formal specification languages", "High-integrity programming languages", "History of computing in the United Kingdom", "Procedural programming languages"]
related: ["[[Ada (programming language)]]", "[[ALGOL 68]]", "[[CS-4 (programming language)]]", "[[ELAN (programming language)]]", "[[Go (programming language)]]", "[[JADE (programming language)]]", "[[Joyce (programming language)]]", "[[Mesa (programming language)]]", "[[Nim (programming language)]]", "[[Occam (programming language)]]"]
---

# SPARK (programming language)

SPARK is a formally defined computer programming language based on the Ada programming language, intended for developing high-integrity software used in systems where predictable and highly reliable operation is essential. It facilitates developing applications that demand safety, security, or business integrity. It has especially found use in real-time computing and embedded systems where issues of safety-criticality or computer security are paramount.
Originally, three versions of SPARK existed (SPARK83, SPARK95, SPARK2005), based on Ada 83, Ada 95, and Ada 2005 respectively.
A fourth version, SPARK 2014, based on Ada 2012, was released on April 30, 2014. SPARK 2014 is a complete re-design of the language and supports software verification tools.
The SPARK language consists of a well-defined subset of the Ada language that uses contracts to describe the specification of components in a form that is suitable for both static and dynamic verification. SPARK is also designed to eliminate all language constructs that can cause unpredictable behavior.
In SPARK83/95/2005, the contracts are encoded in Ada comments and so are ignored by any standard Ada compiler, but are processed by the SPARK Examiner and its associated tools. These earlier versions focus on static verification of contracts.
SPARK 2014, in contrast, uses Ada 2012's built-in syntax of aspects to express contracts, bringing them into the core of the language. The main tool for SPARK 2014 (GNATprove) is based on the GNAT/GCC infrastructure, and re-uses almost all of the GNAT Ada 2012 front-end.

## Related

- [[Ada (programming language)]]
- [[ALGOL 68]]
- [[CS-4 (programming language)]]
- [[ELAN (programming language)]]
- [[Go (programming language)]]
- [[JADE (programming language)]]
- [[Joyce (programming language)]]
- [[Mesa (programming language)]]
- [[Nim (programming language)]]
- [[Occam (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SPARK_(programming_language)