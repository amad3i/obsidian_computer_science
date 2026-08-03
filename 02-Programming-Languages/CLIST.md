---
title: "CLIST"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/CLIST"
wikipedia_categories: ["Command shells", "IBM mainframe operating systems", "Procedural programming languages", "Scripting languages", "Text-oriented programming languages"]
related: ["[[Rexx]]", "[[Perl]]", "[[PHP]]", "[[PowerShell]]", "[[Rc (Unix shell)]]", "[[Tcl (programming language)]]", "[[Almquist shell]]", "[[AMPL]]", "[[AWK]]", "[[Bash (Unix shell)]]"]
---

# CLIST

CLIST (Command List; pronounced "C-List") is a procedural programming language for Time Sharing Option (TSO) in SVS and MVS systems. It originated in OS/360 Release 20 and has assumed a secondary role since the availability of Rexx in TSO/E Version 2. In its basic form, a CLIST program is a list of commands to be executed in strict sequence. OS/VS2 R3.6 (MVS) added If-Then-Else logic and loop constructs to CLIST. The term CLIST is also used for command lists written by users of NetView.
CLIST is an interpreted language.  That is, the computer must translate a CLIST every time the program is executed.  CLISTs therefore tend to be slower than programs written in compiled languages such as COBOL, FORTRAN, or PL/1.  (A program written in a compiled language is translated once to create a "load module" or executable.)
CLIST can read/write MVS files and read/write from/to a TSO terminal. It can read parameters from the caller and also features a function to hold global variables and pass them between CLISTs. A CLIST can also call an MVS application program (written in COBOL or  PL/I, for example). CLISTs can be run in background. CLISTs can display TSO I/O screens and menus by using ISPF dialog services.
Compare the function of CLIST with that provided by REXX.

## Related

- [[Rexx]]
- [[Perl]]
- [[PHP]]
- [[PowerShell]]
- [[Rc (Unix shell)]]
- [[Tcl (programming language)]]
- [[Almquist shell]]
- [[AMPL]]
- [[AWK]]
- [[Bash (Unix shell)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CLIST