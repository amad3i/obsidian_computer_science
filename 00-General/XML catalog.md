---
title: "XML catalog"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/XML_catalog"
wikipedia_categories: ["Computer file formats", "Markup languages", "XML"]
related: ["[[Efficient XML Interchange]]", "[[Office Open XML]]", "[[Office Open XML file formats]]", "[[People Finder Interchange Format]]", "[[XML]]", "[[XML log]]", "[[Analyzed Layout and Text Object]]", "[[COCOA (digital humanities)]]", "[[Component content management system]]", "[[Compound Document Format]]"]
---

# XML catalog

XML documents typically refer to external entities, for example the public and/or system ID for the Document Type Definition. These external relationships are expressed using URIs, typically as URLs.
However absolute URLs only work when the network can reach them. Relying on remote resources makes XML processing susceptible to both planned and unplanned network downtime.
Relative URLs are only useful in the context where they were initially created. For example, the URL "../../xml/dtd/docbookx.xml" will usually only be useful in very limited circumstances.
One way to avoid these problems is to use an entity resolver (a standard part of SAX) or a URI Resolver (a standard part of JAXP). A resolver can examine the URIs of the resources being requested and determine how best to satisfy those requests. The XML catalog is a document describing a mapping between external entity references and locally cached equivalents.

## Related

- [[Efficient XML Interchange]]
- [[Office Open XML]]
- [[Office Open XML file formats]]
- [[People Finder Interchange Format]]
- [[XML]]
- [[XML log]]
- [[Analyzed Layout and Text Object]]
- [[COCOA (digital humanities)]]
- [[Component content management system]]
- [[Compound Document Format]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/XML_catalog