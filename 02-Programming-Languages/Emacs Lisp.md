---
title: "Emacs Lisp"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Emacs_Lisp"
wikipedia_categories: ["Dynamically scoped programming languages", "Emacs", "Free and open source compilers", "Free and open source interpreters", "GNU Project Lisp programming language implementations", "Lisp programming language family", "Programming languages created in 1985", "Scripting languages"]
related: ["[[AutoLISP]]", "[[GNU Guile]]", "[[Julia (programming language)]]", "[[AMPL]]", "[[AWK]]", "[[Bash (Unix shell)]]", "[[Cadence SKILL]]", "[[ChatScript]]", "[[Ciao (programming language)]]", "[[EiffelStudio]]"]
---

# Emacs Lisp

Emacs Lisp is a Lisp dialect made for GNU Emacs.
It is used for implementing most of the editing functionality built into Emacs, the remainder being written in C, as is the Lisp interpreter.
Emacs Lisp code is used to modify, extend and customize Emacs.
Those not wanting to write the code themselves can use the Customize function instead. It provides a set of preferences pages allowing the user to set options and preview their effect in the running Emacs session. 
When the user saves their changes,
Customize simply writes the necessary Emacs Lisp code to the user's config file, which can be set to a special file that only Customize uses, to avoid the possibility of altering the user's own file.
Besides being a programming language that can be compiled to bytecode
and to machine code,
Emacs Lisp can also function as an interpreted scripting language, much like the Unix Bourne shell or Perl, by calling Emacs in batch mode. 
In this way it may be called from the command line or via an executable file, and its editing functions, such as buffers and movement commands are available to the program just as in the normal mode. No user interface is presented when Emacs is started in batch mode; it simply executes the passed-in script and exits, displaying any output from the script.
Emacs Lisp is also termed Elisp, although there are also older, unrelated Lisp dialects with that name.

## Related

- [[AutoLISP]]
- [[GNU Guile]]
- [[Julia (programming language)]]
- [[AMPL]]
- [[AWK]]
- [[Bash (Unix shell)]]
- [[Cadence SKILL]]
- [[ChatScript]]
- [[Ciao (programming language)]]
- [[EiffelStudio]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Emacs_Lisp