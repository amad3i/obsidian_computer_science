---
title: "Termcap"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Termcap"
wikipedia_categories: ["1978 software", "Computer data", "Databases", "Termcap", "Text mode"]
related: ["[[Agnostic (data)]]", "[[Altibase]]", "[[Autocommit]]", "[[Backup]]", "[[Big data]]", "[[Brooklyn Bridge (software)]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[Change data capture]]", "[[ChromaDB]]"]
---

# Termcap

Termcap (terminal capability) is a legacy software library and database used on Unix-like computers that enables programs to use display computer terminals in a terminal-independent manner, which greatly simplifies the process of writing portable text mode applications. It was superseded by the terminfo database used by ncurses, tput, and other programs. 
A termcap database can describe the capabilities of hundreds of different display terminals. This allows programs to have character-based display output, independent of the type of terminal. On-screen text editors such as vi and Emacs are examples of programs that may use termcap. Other programs are listed in the  Termcap category. Access to the termcap database was usually provided by separate libraries, e.g. GNU Termcap.
Examples of what the database describes:

how many columns wide the display is
what string to send to move the cursor to an arbitrary position (including how to encode the row and column numbers)
how to scroll the screen up one or several lines
how much padding is needed for such a scrolling operation.

## Related

- [[Agnostic (data)]]
- [[Altibase]]
- [[Autocommit]]
- [[Backup]]
- [[Big data]]
- [[Brooklyn Bridge (software)]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[Change data capture]]
- [[ChromaDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Termcap