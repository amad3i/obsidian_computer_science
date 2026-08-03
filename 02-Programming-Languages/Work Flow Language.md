---
title: "Work Flow Language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Work_Flow_Language"
wikipedia_categories: ["ALGOL 60 dialect", "Burroughs mainframe computers", "Mainframe computer software", "Scripting languages"]
related: ["[[ActionScript]]", "[[Active Scripting]]", "[[ActivePerl]]", "[[Adobe ColdFusion]]", "[[Almquist shell]]", "[[AMPL]]", "[[AngelScript]]", "[[Apache Groovy]]", "[[AppleScript]]", "[[AppleScript Editor]]"]
---

# Work Flow Language

Work Flow Language, or WFL ("wiffle") is the process control language for the Burroughs large systems, including the Unisys ClearPath/MCP series, and their operating system Master Control Program. Developed soon after the B5000 in 1961, WFL is the ClearPath equivalent of the Job Control Language (JCL) on IBM mainframes and the shell scripts of Unix-like operating systems. Unlike JCL, WFL is a high-level structured language complete with subroutines (procedures and functions) with arguments and high-level program control flow instructions. WFL programs are compiled to binary executables like any other MCP subject.
WFL  is used for high-level system operations, such as running tasks, moving and copying files, providing high-level recoverability. Thus it is not a general purpose language in that you would not use it to do general computations. You can open and close files to check their attributes for example; however, you cannot read or change their contents in WFL – that you do in a general purpose language, and invoke it as a task from WFL.
WFL has a high-level ALGOL-like readable syntax. It has none of the low-level assembler-like commands of JCL like //SYSIN DD, etc. in order to connect hardware devices and open files for programs. All WFL constructs deal with the high-level abstractions of tasks and files. Parameters are also real HLL parameters, not the $1, $2... style position parameters of shell scripts.
WFL also has an instruction block command which is used to give operators instructions needed to run the current job. These instructions are displayed using the 'IB' operator command.
WFL was a compiled language on the medium systems.  Because some OS interfaces may change from release to release, Medium Systems WFL code included a copy of the source in the object file. Upon executing a WFL job it would check to determine if the object was compatible with the OS version.  If not it would trigger a recompile of the object using the source embedded in the object code.

## Related

- [[ActionScript]]
- [[Active Scripting]]
- [[ActivePerl]]
- [[Adobe ColdFusion]]
- [[Almquist shell]]
- [[AMPL]]
- [[AngelScript]]
- [[Apache Groovy]]
- [[AppleScript]]
- [[AppleScript Editor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Work_Flow_Language