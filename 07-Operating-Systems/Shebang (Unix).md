---
title: "Shebang (Unix)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Shebang_(Unix)"
wikipedia_categories: ["Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Ldconfig]]", "[[Line discipline]]", "[[Line Printer Daemon protocol]]", "[[List of input methods for Unix platforms]]"]
---

# Shebang (Unix)

In computing, a shebang is the character sequence #!, consisting of the characters number sign (also known as sharp or hash) and exclamation mark (also known as bang), at the beginning of a script. It is also called sharp-exclamation, sha-bang, hashbang, pound-bang, or hash-pling.
When a text file with a shebang is used as if it were an executable in a Unix-like operating system, the program loader mechanism parses the rest of the file's initial line as an interpreter directive. The loader executes the specified interpreter program, passing to it as an argument the path that was initially used when attempting to run the script, so that the program may use the file as input data. For example, if a script is named with the path path/to/script, and it starts with the line #!/bin/sh, then the program loader is instructed to run the program /bin/sh, passing path/to/script as the first argument.
The shebang line is usually ignored by the interpreter, because the "#" character is a comment marker in many scripting languages; some language interpreters that do not use the hash mark to begin comments still may ignore the shebang line in recognition of its purpose.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Ldconfig]]
- [[Line discipline]]
- [[Line Printer Daemon protocol]]
- [[List of input methods for Unix platforms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shebang_(Unix)