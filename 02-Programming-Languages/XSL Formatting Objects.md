---
title: "XSL Formatting Objects"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/XSL_Formatting_Objects"
wikipedia_categories: ["Markup languages", "Page description languages", "Typesetting programming languages", "World Wide Web Consortium standards", "XML-based standards"]
related: ["[[Hypertext Application Language]]", "[[Speech Synthesis Markup Language]]", "[[Synchronized Multimedia Integration Language]]", "[[VoiceXML]]", "[[XBL]]", "[[XHTML]]", "[[XLink]]", "[[XProc]]", "[[XSL]]", "[[XSLT]]"]
---

# XSL Formatting Objects

XSL-FO (XSL Formatting Objects) is a markup language for XML document formatting that is most often used to generate PDF files. It has largely been superseded by the CSS3 but is still maintained for legacy systems.
It is an intermediary file format with the purpose of generating paged, printed media. The intended workflow is to transform an XML file into XSL-FO by writing and running a script in the XSLT programming language and then transform the XSL-FO file into PDF or other formats with a software called XSL-FO processor. The XSLT script only needs to be written once for each document type.
The XSL-FO specification was originally published under the ambiguous title XSL 1.0 in October 2001 declaring XSLT to be the other half but only linking the 1999 XSLT specification rather than including it.  Version 1.1 was published as XSL 1.1 in December 2006.
The last update for the 2.0 Working Draft was in January 2012, and its Working Group closed in November 2013.
The XSLT language itself was originally conceived only to transform to XSL-FO but is now used for more general XML transformations.
The XSL-FO specification allows different FO processors to have varying responses with regard to the resultant generated pages.
For example, different processors may even use different hyphenation algorithms, ranging from very simple to more complex hyphenation algorithms that take into account whether the previous or next line also is hyphenated. This can substantially change the layout. 
FO works best for a single flowing span of fairly contiguous text, with various repeating information built into the margins of a page. This is as opposed to complex layouts used in newspapers or magazines.

## Related

- [[Hypertext Application Language]]
- [[Speech Synthesis Markup Language]]
- [[Synchronized Multimedia Integration Language]]
- [[VoiceXML]]
- [[XBL]]
- [[XHTML]]
- [[XLink]]
- [[XProc]]
- [[XSL]]
- [[XSLT]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/XSL_Formatting_Objects