---
title: "MetaPost"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/MetaPost"
wikipedia_categories: ["Declarative programming languages", "Domain-specific programming languages", "Free TeX software", "PostScript", "Programming languages created in 1994", "Public-domain software", "Vector graphics markup languages"]
related: ["[[Extensible Application Markup Language]]", "[[Graphics Layout Engine]]", "[[XProc]]", "[[XSLT]]", "[[QL]]", "[[Alpha (programming language)]]", "[[Apple Media Tool]]", "[[APT (programming language)]]", "[[ASCEND]]", "[[Atom (programming language)]]"]
---

# MetaPost

MetaPost refers to both a programming language and the interpreter of the MetaPost programming language. Both are derived from Donald Knuth's Metafont language and interpreter. MetaPost produces vector graphic diagrams from a geometric/algebraic description. The language shares Metafont's declarative syntax for manipulating lines, curves, points and geometric transformations. However,

Metafont is set up to produce fonts, in the form of image files (in .gf format) with associated font metric files (in .tfm format), whereas MetaPost produces EPS, SVG, or PNG files
The output of Metafont consists of the fonts at a fixed resolution in a raster-based format, whereas MetaPost's output is vector-based graphics (lines, Bézier curves)
Metafont output is monochrome, whereas MetaPost uses RGB or CMYK colors.
The MetaPost language can include text labels on the diagrams, either strings from a specified font, or anything else that can be typeset with TeX.
Starting with version 1.8, Metapost allows floating-point arithmetic with 64 bits (default: 32 bit fixed-point arithmetic)
Many of the limitations of MetaPost derive from features of Metafont. For instance, MetaPost does not support all features of PostScript. Most notably, paths can have only one segment (so that regions are simply connected), and regions can be filled only with uniform colours. PostScript level 1 supports tiled patterns and PostScript 3 supports Gouraud shading.

## Related

- [[Extensible Application Markup Language]]
- [[Graphics Layout Engine]]
- [[XProc]]
- [[XSLT]]
- [[QL]]
- [[Alpha (programming language)]]
- [[Apple Media Tool]]
- [[APT (programming language)]]
- [[ASCEND]]
- [[Atom (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MetaPost