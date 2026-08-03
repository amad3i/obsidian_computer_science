---
title: "PowerShell"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/PowerShell"
wikipedia_categories: [".NET programming languages", "Configuration management", "Dynamically typed programming languages", "Formerly proprietary software", "Interpreters (computing)", "Microsoft free software", "Microsoft programming languages", "Object-oriented programming languages"]
related: ["[[F- (programming language)]]", "[[StaDyn]]", "[[Apache Groovy]]", "[[APL (programming language)]]", "[[Axum (programming language)]]", "[[Boo (programming language)]]", "[[C Sharp (programming language)]]", "[[Ciao (programming language)]]", "[[Dafny]]", "[[Dart (programming language)]]"]
---

# PowerShell

PowerShell is a shell program developed by Microsoft for task automation and configuration management. As is typical for a shell, it provides a command-line interpreter for interactive use and a script interpreter for automation via a language defined for it. Originally only for Windows, known as Windows PowerShell, it was made open-source and cross-platform on August 18, 2016, with the introduction of PowerShell Core. The former is built on the .NET Framework and the latter on .NET (previously .NET Core).
PowerShell is bundled with current versions of Windows and can be installed on macOS and Linux. Since Windows 10 build 14971, PowerShell replaced Command Prompt as the default command shell exposed by File Explorer.
In PowerShell, administrative tasks are generally performed via cmdlets (pronounced command-lets), which are specialized .NET classes implementing a particular operation. These work by accessing data in different data stores, like the file system or Windows Registry, which are made available to PowerShell via providers. Third-party developers can add cmdlets and providers to PowerShell. Cmdlets may be used by scripts, which may in turn be packaged into modules. Cmdlets work in tandem with the .NET API.
PowerShell's support for .NET Remoting, WS-Management, CIM, and SSH enables administrators to perform administrative tasks on both local and remote Windows systems. PowerShell also provides a hosting API with which the PowerShell runtime can be embedded inside other applications. These applications can then use PowerShell functionality to implement certain operations, including those exposed via the graphical interface. This capability has been used by Microsoft Exchange Server 2007 to expose its management functionality as PowerShell cmdlets and providers and implement the graphical management tools as PowerShell hosts which invoke the necessary cmdlets. Other Microsoft applications including Microsoft SQL Server 2008 also expose their management interface via PowerShell cmdlets.
PowerShell includes its own extensive, console-based help (similar to man pages in Unix shells) accessible via the Get-Help cmdlet. Updated local help contents can be retrieved from the Internet via the Update-Help cmdlet. Alternatively, help from the web can be acquired on a case-by-case basis via the -online switch to Get-Help.

## Related

- [[F- (programming language)]]
- [[StaDyn]]
- [[Apache Groovy]]
- [[APL (programming language)]]
- [[Axum (programming language)]]
- [[Boo (programming language)]]
- [[C Sharp (programming language)]]
- [[Ciao (programming language)]]
- [[Dafny]]
- [[Dart (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/PowerShell