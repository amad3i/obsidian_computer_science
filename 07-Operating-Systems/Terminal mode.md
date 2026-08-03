---
title: "Terminal mode"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Terminal_mode"
wikipedia_categories: ["Computer terminals", "Unix"]
related: ["[[Line discipline]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Computer terminal]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Ldconfig]]", "[[Line Printer Daemon protocol]]"]
---

# Terminal mode

A terminal mode is one of a set of possible states of a terminal or pseudo terminal character device in Unix-like systems and determines how characters written to the terminal are interpreted.  In cooked mode data is preprocessed before being given to a program, while raw mode passes the data as-is to the program without interpreting any of the special characters.
The system intercepts special characters in cooked mode and interprets special meaning from them.  Backspace, delete, and Control-D are typically used to enable line-editing for the input to the running programs, and other control characters such as Control-C and Control-Z are used for job control or associated with other signals.  The precise definition of what constitutes a cooked mode is operating system-specific.
For example, if "ABC<Backspace>D" is given as an input to a program through a terminal character device in cooked mode, the program gets "ABD". But, if the terminal is in raw mode, the program gets the characters "ABC" followed by the Backspace character and followed by "D". In cooked mode, the terminal line discipline processes the characters "ABC<Backspace>D" and presents only the result ("ABD") to the program.
Technically, the term cooked mode should be associated only with streams that have a terminal line discipline, but generally it is applied to any system that does some amount of preprocessing.

## Related

- [[Line discipline]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Computer terminal]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Ldconfig]]
- [[Line Printer Daemon protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Terminal_mode