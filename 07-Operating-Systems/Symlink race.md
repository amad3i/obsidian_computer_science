---
title: "Symlink race"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Symlink_race"
wikipedia_categories: ["Computer security exploits", "Unix", "Unix stubs"]
related: ["[[Line discipline]]", "[[Message of the day]]", "[[Qsub]]", "[[Spl (Unix)]]", "[[Utmp]]", "[[Words (Unix)]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Armitage (computing)]]", "[[Buffer overflow]]", "[[Busdma]]"]
---

# Symlink race

A symlink race is a kind of software security vulnerability that results from a program creating files in an insecure manner. A malicious user can create a symbolic link to a file not otherwise accessible to them. When the privileged program creates a file of the same name as the symbolic link, it actually creates the linked-to file instead, possibly inserting content desired by the malicious user (see example below), or even provided by the malicious user (as input to the program).
It is called a "race" because in its typical manifestation, the program checks to see if a file by that name already exists; if it does not exist, the program then creates the file. An attacker must create the link in the interval between the check and when the file is created.
A symlink race can happen with antivirus products that decide they will quarantine or delete a suspicious file, and then go ahead and do that. During the interval between decision and action, malicious software can replace the suspicious file with a system or antivirus file that the malicious software wants overwritten.

## Related

- [[Line discipline]]
- [[Message of the day]]
- [[Qsub]]
- [[Spl (Unix)]]
- [[Utmp]]
- [[Words (Unix)]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Armitage (computing)]]
- [[Buffer overflow]]
- [[Busdma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Symlink_race