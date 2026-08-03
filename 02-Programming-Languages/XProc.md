---
title: "XProc"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/XProc"
wikipedia_categories: ["Concurrent programming languages", "Data processing", "Declarative programming languages", "Domain-specific programming languages", "Markup languages", "World Wide Web Consortium standards", "XML-based programming languages", "XML-based standards"]
related: ["[[XSLT]]", "[[Synchronized Multimedia Integration Language]]", "[[VoiceXML]]", "[[Enterprise Mashup Markup Language]]", "[[Extensible Application Markup Language]]", "[[Hypertext Application Language]]", "[[Speech Synthesis Markup Language]]", "[[XBL]]", "[[XHTML]]", "[[XLink]]"]
---

# XProc

XProc is an XML transformation language for processing documents in pipelines: chaining conversions and other steps together to  achieve the desired results. It can handle documents in  XML, HTML, JSON, text and binary.
The current (stable) version is 3.1. While XProc 1.0 is a W3C Recommendation, XProc 3.1 is a standard developed by the W3C XProc Next Community Group.
Its main characteristics are:

XProc is a programming language, expressed in XML, in which you can write pipelines.
An XProc pipeline takes data as its input (often XML) and passes this through specialized steps to produce end results.
Steps range from simple ones, like adding attributes, to more complex stuff like splitting/combining/pruning, transformations with XSLT and XQuery, validations against schemas, etc.
Within a pipeline you can do things like working with variables, branching, looping, catch errors, etc. Everything is based on the data flowing through.
XProc pipelines are not limited to a linear succession of steps. They can fork and merge.
XProc allows you to create custom steps by combining other steps. These custom steps can be used just like any other. Therefore, pipelines and steps are interchangeable concepts in XProc.
Custom steps can be collected into libraries.
XProc aids in the housekeeping surrounding the processing, like inspecting directories, reading documents from zip files, writing things to disk, etc
There is software that can execute these pipelines, the so-called XProc processors.

## Related

- [[XSLT]]
- [[Synchronized Multimedia Integration Language]]
- [[VoiceXML]]
- [[Enterprise Mashup Markup Language]]
- [[Extensible Application Markup Language]]
- [[Hypertext Application Language]]
- [[Speech Synthesis Markup Language]]
- [[XBL]]
- [[XHTML]]
- [[XLink]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/XProc