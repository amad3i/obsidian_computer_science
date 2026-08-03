---
title: "Data set (IBM mainframe)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_set_(IBM_mainframe)"
wikipedia_categories: ["Computer file systems", "Computer files", "Data management", "IBM mainframe operating systems"]
related: ["[[Access method]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Clustered file system]]", "[[Computer file]]", "[[Filename mangling]]", "[[Object storage]]", "[[Single-source publishing]]", "[[Tagsistant]]", "[[Abstraction (computer science)]]"]
---

# Data set (IBM mainframe)

In the context of IBM mainframe computers in the IBM System/360 line and its successors, a data set (IBM preferred) or  dataset is a computer file having a record organization. Use of this term began with, e.g., DOS/360 and OS/360, and is still used by their successors, including the current VSE and z/OS. Documentation for these systems historically preferred this term rather than file.
A data set is typically stored on a direct access storage device (DASD) or magnetic tape, however unit record devices, such as punch card readers, card punches, line printers and page printers can provide input/output (I/O) for a data set (file).
Data sets are not unstructured streams of bytes, but rather are organized in various logical record and block structures determined by the DSORG (data set organization), RECFM (record format), and other parameters. These parameters are specified at the time of the data set allocation (creation), for example with Job Control Language DD statements. Within a running program they are stored in the Data Control Block (DCB) or Access Control Block (ACB), which are data structures used to access data sets using access methods.
Records in a data set may be fixed, variable, or “undefined” length.

## Related

- [[Access method]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Clustered file system]]
- [[Computer file]]
- [[Filename mangling]]
- [[Object storage]]
- [[Single-source publishing]]
- [[Tagsistant]]
- [[Abstraction (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_set_(IBM_mainframe)