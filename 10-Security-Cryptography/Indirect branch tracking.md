---
title: "Indirect branch tracking"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Indirect_branch_tracking"
wikipedia_categories: ["Computer security", "Computer security stubs", "Control flow integrity"]
related: ["[[Centurion Guard]]", "[[Control-flow integrity]]", "[[Cyber attribution]]", "[[Cyber Discovery]]", "[[DREAD (risk assessment model)]]", "[[Psychology in cybersecurity]]", "[[Security and Privacy in Computer Systems]]", "[[Security information management]]", "[[Site Security Handbook]]", "[[Vx-underground]]"]
---

# Indirect branch tracking

Indirect branch tracking (IBT), also known as branch target identification (BTI), is a control flow integrity mechanism implemented on some Intel x86-64 and ARM-64 processors. IBT is designed to protect against computer security exploits that use indirect branch instructions to jump into code in unintended ways, such as return-oriented programming.
It creates a special "branch target" instructions that have no function other than to mark a location as a valid indirect branch target, with the processor capable of being put into a mode where it will raise an exception if an indirect branch is made to a location without a branch target instruction.

## Related

- [[Centurion Guard]]
- [[Control-flow integrity]]
- [[Cyber attribution]]
- [[Cyber Discovery]]
- [[DREAD (risk assessment model)]]
- [[Psychology in cybersecurity]]
- [[Security and Privacy in Computer Systems]]
- [[Security information management]]
- [[Site Security Handbook]]
- [[Vx-underground]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Indirect_branch_tracking