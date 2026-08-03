---
title: "Knuth–Plass line-breaking algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Knuth–Plass_line-breaking_algorithm"
wikipedia_categories: ["Algorithms", "Typography"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Knuth–Plass line-breaking algorithm

The Knuth–Plass algorithm is a line-breaking algorithm designed for use in Donald Knuth's typesetting program TeX. It integrates the problems of text justification and hyphenation into a single algorithm by using a discrete dynamic programming method to minimize a loss function that attempts to quantify the aesthetic qualities desired in the finished output.
The algorithm works by dividing the text into a stream of three kinds of objects: boxes, which are non-resizable chunks of content, glue, which are flexible, resizeable elements, and penalties, which represent places where breaking is undesirable (or, if negative, desirable). The loss function, known as "badness", is defined in terms of the deformation of the glue elements, and any extra penalties incurred through line breaking.
Making hyphenation decisions follows naturally from the algorithm, but the choice of possible hyphenation points within words, and optionally their preference weighting, must be performed first, and that information inserted into the text stream in advance. Knuth and Plass' original algorithm does not include page breaking, but may be modified to interface with a pagination algorithm, such as the algorithm designed by Plass in his PhD thesis.
Typically, the cost function for this technique should be modified so that it does not count the space left on the final line of a paragraph; this modification allows a paragraph to end in the middle of a line without penalty. The same technique can also be extended to take into account other factors such as the number of lines or costs for hyphenating long words.

## Related

- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]
- [[Algorithmic mechanism design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Knuth–Plass_line-breaking_algorithm