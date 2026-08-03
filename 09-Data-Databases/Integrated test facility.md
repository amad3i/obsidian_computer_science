---
title: "Integrated test facility"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Integrated_test_facility"
wikipedia_categories: ["Database stubs", "Databases"]
related: ["[[Data store]]", "[[Database dump]]", "[[Halloween Problem]]", "[[Hekaton (database)]]", "[[Index locking]]", "[[Information schema]]", "[[International Clinical Trials Registry Platform]]", "[[Load file]]", "[[Locks with ordered sharing]]", "[[Pseudocolumn]]"]
---

# Integrated test facility

An integrated test facility (ITF) creates a fictitious entity in a database to process test transactions simultaneously with live input. 
ITF can be used to incorporate test transactions into a normal production run of a system. Its advantage is that periodic testing does not require separate test processes. However, careful planning is necessary, and test data must be isolated from production data. 
Moreover, ITF validates the correct operation of a transaction in an application, but it does not ensure that a system is being operated correctly. Integrated test facility is considered a useful audit tool during an IT audit because it uses the same programs to compare processing using independently calculated data. This involves setting up dummy entities on an application system and processing test or production data against the entity as a means of verifying processing accuracy.

## Related

- [[Data store]]
- [[Database dump]]
- [[Halloween Problem]]
- [[Hekaton (database)]]
- [[Index locking]]
- [[Information schema]]
- [[International Clinical Trials Registry Platform]]
- [[Load file]]
- [[Locks with ordered sharing]]
- [[Pseudocolumn]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Integrated_test_facility