---
title: "Terminfo"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Terminfo"
wikipedia_categories: ["1980s software", "Database management systems", "Terminfo", "Text mode"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Terminfo

Terminfo is a library and database that enables programs to use display terminals in a device-independent manner. Mary Ann Horton implemented the first terminfo library in 1981–1982 as an improvement over termcap. The improvements include

faster access to stored terminal descriptions,
longer, more understandable names for terminal capabilities and
general expression evaluation for strings sent to the terminal.
Terminfo was included with UNIX System V Release 2 and soon became the preferred form of terminal descriptions in System V, rather than termcap (which BSD continued to use).  This was imitated in pcurses in 1982–1984 by Pavel Curtis, and was available on other UNIX implementations, adapting or incorporating fixes from Mary Horton.  For more information, refer to the posting on the comp.sources.unix newsgroup from December 1986.
A terminfo database can describe the capabilities of hundreds of different display terminals.  This allows external programs to be able to have character-based display output, independent of the type of terminal.
Some configurations are:

Number of lines on the screen
Mono mode; suppress color
Use visible bell instead of beep

## Related

- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]
- [[Bidirectionalization]]
- [[Bigtable]]
- [[Block contention]]
- [[Candidate key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Terminfo