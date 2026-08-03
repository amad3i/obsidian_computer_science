---
title: "Nessus Attack Scripting Language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Nessus_Attack_Scripting_Language"
wikipedia_categories: ["Free security software", "Pentesting software toolkits", "Scripting languages", "Software testing tools"]
related: ["[[DejaGnu]]", "[[Metasploit]]", "[[ACARM-ng]]", "[[ActionScript]]", "[[Active Scripting]]", "[[ActivePerl]]", "[[Adobe ColdFusion]]", "[[Almquist shell]]", "[[AMPL]]", "[[AngelScript]]"]
---

# Nessus Attack Scripting Language

The Nessus Attack Scripting Language, usually referred to as NASL, is a scripting language that is used by vulnerability scanners like Nessus and OpenVAS. With NASL specific attacks can be automated, based on known vulnerabilities.
Tens of thousands of plugins have been written in NASL for Nessus and OpenVAS. Files that are written in this language usually get the file extension .nasl. For the exploitation of a zero day attack it is possible for an end user of Nessus or OpenVAS to write custom code in NASL which is executed by these vulnerability scanners.
In earlier versions of Nessus, a binary called nasl or nasl.exe was provided that could interpret NASL code to perform vulnerability scans. In later versions of Nessus, this should be done via an API that is provided by this software.
An example of executing a NASL plugin 'myzeroday.nasl' on Windows, a command such as the following
could be invoked:
nasl.exe -t 127.0.0.1 "C:\temp\myzeroday.nasl"
An equivalent example of a Linux or UNIX command could look like this:
nasl -t 127.0.0.1 /tmp/myzeroday.nasl
If the plugin, in this example myzeroday.nasl, is placed in the same directory where other NASL plugins are located, it can also be included in standard scans by Nessus or OpenVAS, via the Web GUI or an API.
Many of the specifications of the formal language are similar to those of the programming language C and the scripting language Perl and those of other languages. Control flow such as the for loop, the if and if-else statements are part of the language and comments are preceded by a hash.
An example of "Hello World" in NASL is:
display("Hello World\n");
In the release notes of Nessus 6.10.0 of 1/31/2017, a new NASL compiler for faster plugins was mentioned.

## Related

- [[DejaGnu]]
- [[Metasploit]]
- [[ACARM-ng]]
- [[ActionScript]]
- [[Active Scripting]]
- [[ActivePerl]]
- [[Adobe ColdFusion]]
- [[Almquist shell]]
- [[AMPL]]
- [[AngelScript]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nessus_Attack_Scripting_Language