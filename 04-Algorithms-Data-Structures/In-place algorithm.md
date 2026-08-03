---
title: "In-place algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/In-place_algorithm"
wikipedia_categories: ["Algorithms"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# In-place algorithm

In computer science, an in-place algorithm is an algorithm that operates directly on the input data structure without requiring extra space proportional to the input size. In other words, it modifies the input in place, without creating a separate copy of the data structure. An algorithm which is not in-place is sometimes called not-in-place or out-of-place.
In-place can have slightly different meanings. In its strictest form, the algorithm can only have a constant amount of extra space, counting everything including function calls and pointers. However, this form is very limited as simply having an index to a length n array requires O(log n) bits. More broadly, in-place means that the algorithm does not use extra space for manipulating the input but may require a small though non-constant extra space for its operation. Usually, this space is O(log n), though sometimes anything in o(n) is allowed. Note that space complexity also has varied choices in whether or not to count the index lengths as part of the space used. Often, the space complexity is given in terms of the number of indices or pointers needed, ignoring their length. In this article, we refer to total space complexity (DSPACE), counting pointer lengths. Therefore, the space requirements here have an extra log n factor compared to an analysis that ignores the lengths of indices and pointers.  
An algorithm may or may not count the output as part of its space usage. Since in-place algorithms usually overwrite their input with output, no additional space is needed. When writing the output to write-only memory or a stream, it may be more appropriate to only consider the working space of the algorithm. In theoretical applications such as log-space reductions, it is more typical to always ignore output space (in these cases it is more essential that the output is write-only).

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

- Wikipedia: https://en.wikipedia.org/wiki/In-place_algorithm