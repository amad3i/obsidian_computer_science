---
title: "Year 2038 problem"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Year_2038_problem"
wikipedia_categories: ["Future problems", "Linux", "Operating system technology", "Software bugs", "Time formatting and storage bugs", "Unix"]
related: ["[[Sysctl]]", "[[Soname]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[AI takeover]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]"]
---

# Year 2038 problem

The year 2038 problem (also known as Y2038, Y2K38, Y2K38 superbug, or the Epochalypse) is a time computing problem that leaves some computer systems unable to represent times after 03:14:07 UTC on 19 January 2038.
The problem exists in systems which measure Unix time—the number of seconds elapsed since the Unix epoch (00:00:00 UTC on 1 January 1970)—and store it in a signed 32-bit integer. When the data type's maximum value is exceeded, the integer will overflow to its minimum value, which systems will interpret as in the past. The problem resembles the year 2000 problem, but arises from limitations in base-2 (binary) time representation, rather than base-10.
Computer systems that use time for critical computations may encounter fatal errors if the year 2038 problem is not addressed. Some applications that use future dates have already encountered the bug. The most vulnerable systems are those which are infrequently or never updated, such as legacy and embedded systems. Modern systems and software updates address this problem by using signed 64-bit integers, which will take 292 billion years to overflow—approximately 21 times the estimated current age of the universe.

## Related

- [[Sysctl]]
- [[Soname]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[AI takeover]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Year_2038_problem