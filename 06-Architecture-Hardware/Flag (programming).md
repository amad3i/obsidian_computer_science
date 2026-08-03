---
title: "Flag (programming)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Flag_(programming)"
wikipedia_categories: ["Central processing unit", "Computer science stubs", "Digital registers", "Operating system stubs", "Operating system technology", "Programming idioms"]
related: ["[[Control register]]", "[[CPU shielding]]", "[[Dirty bit]]", "[[Login session]]", "[[Opaque binary blob]]", "[[Processor register]]", "[[Protection ring]]", "[[Quaject]]", "[[Single-user mode]]", "[[X86 debug register]]"]
---

# Flag (programming)

In computer programming, a flag can refer to one or more bits that are used to store a binary value or a Boolean variable for signaling special code conditions, such as file empty or full queue statuses.
Flags may be found as members of a defined data structure, such as a database record, and the meaning of the value contained in a flag will generally be defined in relation to the data structure it is part of.  In many cases, the binary value of a flag will be understood to represent one of several possible states or statuses.  In other cases, the binary values may represent one or more attributes in a bit field, often related to abilities or permissions, such as "can be written to" or "can be deleted".  However, there are many other possible meanings that can be assigned to flag values.  One common use of flags is to mark or designate data structures for future processing.
Within microprocessors and other logic devices, flags are commonly used to control or indicate the intermediate or final state or outcome of different operations.  Microprocessors typically have, for example, a status register that is composed of such flags, and the flags are used to indicate various post-operation conditions, such as when there has been an arithmetic overflow.  The flags can be utilized in subsequent operations, such as in processing conditional jump instructions. For example a je (Jump if Equal) instruction in the x86 assembly language will result in a jump if the Z (zero) flag was set by some previous operation.
A command line switch is also referred to as a "flag".  Command line programs often start with an option parser that translates command line switches into flags in the sense of this article.

## Related

- [[Control register]]
- [[CPU shielding]]
- [[Dirty bit]]
- [[Login session]]
- [[Opaque binary blob]]
- [[Processor register]]
- [[Protection ring]]
- [[Quaject]]
- [[Single-user mode]]
- [[X86 debug register]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Flag_(programming)