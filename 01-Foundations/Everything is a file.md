---
title: "Everything is a file"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Everything_is_a_file"
wikipedia_categories: ["Information theory", "Unix file system technology"]
related: ["[[-dev-full]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]", "[[Bandwidth extension]]"]
---

# Everything is a file

"Everything is a file" is an approach to interface design in Unix derivatives.
While this turn of phrase does not as such figure as a Unix design principle or philosophy,
it is a common way to analyse designs, and informs the design of new interfaces in a way that prefers, in rough order of import:

representing objects as file descriptors instead of alternatives like abstract handles or names,
operating on the objects with standard input/output operations, returning byte streams to be interpreted by applications (rather than explicitly structured data), and
allowing the usage or creation of objects by opening or creating files in the global filesystem name space.
The lines between the common interpretations of "file" and "file descriptor" are often blurred when analysing Unix, and nameability of files is the least important part of this principle; thus, it is sometimes described as "Everything is a file descriptor".
This approach is interpreted differently with time, philosophy of each system, and the domain to which it's applied.
The rest of this article demonstrates notable examples of some of those interpretations, and their repercussions.

## Related

- [[-dev-full]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]
- [[Bandwidth extension]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Everything_is_a_file