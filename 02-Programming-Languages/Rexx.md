---
title: "Rexx"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Rexx"
wikipedia_categories: ["Command shells", "Cross-platform software", "IBM mainframe operating systems", "IBM software", "Programming languages created in 1979", "Rexx", "Scripting languages", "Text-oriented programming languages"]
related: ["[[Object REXX]]", "[[CLIST]]", "[[Almquist shell]]", "[[AWK]]", "[[Ciao (programming language)]]", "[[Perl]]", "[[PHP]]", "[[Python (programming language)]]", "[[Tcl (programming language)]]", "[[AMPL]]"]
---

# Rexx

Rexx (restructured extended executor) is a high-level programming language developed at IBM by Mike Cowlishaw. Both proprietary and open source Rexx interpreters exist for a wide range of computing platforms, and compilers exist for IBM mainframe computers. Rexx is used for scripting, application macros and application development. As a general purpose scripting language, Rexx is considered a precursor to Tcl and Python.
Rexx is supported in a variety of environments. It is the primary scripting language in some operating systems including OS/2, MVS, VM, AmigaOS and is used for macros in some software including SPF/PC, KEDIT, THE and ZOC. With an engine installed, Rexx can be used for scripting and macros in programs that use a Windows Scripting Host ActiveX scripting engine (such as VBScript or JScript). Rexx is supplied with VM/SP Release 3 on up, TSO/E Version 2 on up, OS/2 (1.3 and later, where it is officially named Procedures Language/2), AmigaOS Version 2 on up, PC DOS (7.0 or 2000), ArcaOS, and Windows NT 4.0 (Resource Kit: Regina). In the late 1980s, Rexx became the common scripting language for IBM Systems Application Architecture, where it was renamed "SAA Procedure Language REXX".
A script is associated with a Rexx interpreter at runtime in various ways based on context. In mainframe computing, a Rexx script or command is sometimes referred to as an EXEC since that is the name of the file type used for similar CMS EXEC, and EXEC 2 scripts and for Rexx scripts on VM/SP R3 through z/VM. The first line of a script specifies the use of a Rexx interpreter in a comment either by identifying the code as Rexx language or by file path via EXTPROC. On MVS, Rexx scripts may be recognized by the low level qualifier "EXEC" or if the first line fetched from SYSPROC is a comment containing "REXX" then it is treated as Rexx (rather than CLIST), and a script fetched from SYSEXEC must be Rexx. On OS/2, Rexx scripts share the filename extension ".cmd" with other scripting languages, and the first line of the script specifies the interpreter to use. On Linux, Rexx scripts generally begin with a shebang. Rexx macros for Rexx-aware applications use extensions determined by the application.

## Related

- [[Object REXX]]
- [[CLIST]]
- [[Almquist shell]]
- [[AWK]]
- [[Ciao (programming language)]]
- [[Perl]]
- [[PHP]]
- [[Python (programming language)]]
- [[Tcl (programming language)]]
- [[AMPL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rexx