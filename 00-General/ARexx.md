---
title: "ARexx"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/ARexx"
wikipedia_categories: ["AmigaOS", "AmigaOS 4 software", "Amiga APIs", "Amiga development software", "Commodore software", "Inter-process communication", "MorphOS", "Rexx"]
related: ["[[Installer (programming language)]]", "[[CMS Pipelines]]", "[[Advanced Message Queuing Protocol]]", "[[Asynchrony (computer programming)]]", "[[Blitter object]]", "[[Blocking (computing)]]", "[[Client–server model]]", "[[Common Object Request Broker Architecture]]", "[[Component Object Model]]", "[[Computer file]]"]
---

# ARexx

ARexx is a Rexx interpreter for Amiga, written in 1987 by William S. Hawes, with a number of Amiga-specific features beyond standard Rexx. An ARexx script can communicate with software that implements an ARexx port. An Amiga application can define a set of commands and functions for ARexx to address, thus making the capabilities of the software available to an ARexx script. Several applications support running an ARexx script as a macro.
An ARexx script can execute commands and functions in multiple applications which allows a script to integrate the functionality of the applications. For example, an ARexx script could extract data from a database, insert the data into a spreadsheet to perform calculations on the data, then insert tables and charts based on the results into a word processor document.
ARexx allows a script to communicate with applications that are "ARexx compatible" – able to receive commands from ARexx and execute them. Notable examples include: the MicroFiche Filer database application provides extensive ARexx commands, the Textra editor supplied with JForth provides an integrated programming environment, and the AmigaVision multimedia presentation application can control other programs via ARexx.
As in standard Rexx, ARexx uses typeless data representation. Other programming languages distinguish types such as integer, floating point, string, but Rexx treats all data as text (string). This makes writing code easier, but leads to runtime inefficiency and errors. As is often the case in dynamically scoped languages, variables are not declared before using them. They are created on first use.
ARexx provides built-in commands and access to its host Amiga library (rexxsyslib.library) as well as other libraries and functions. An Amiga program with an ARexx port can serve its functionality to an ARexx script. An ARexx script can invoke other ARexx scripts.

## Related

- [[Installer (programming language)]]
- [[CMS Pipelines]]
- [[Advanced Message Queuing Protocol]]
- [[Asynchrony (computer programming)]]
- [[Blitter object]]
- [[Blocking (computing)]]
- [[Client–server model]]
- [[Common Object Request Broker Architecture]]
- [[Component Object Model]]
- [[Computer file]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ARexx