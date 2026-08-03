---
title: "Path (computing)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Path_(computing)"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Path (computing)

A path (or filepath, file path, pathname, or similar) is a string that uniquely identifies an item in a hierarchical file system. Generally, a path is composed of directory names, special format specifiers, and optionally a filename, all separated by delimiters. This delimiter can vary by operating system, but popular, modern systems use the slash /, backslash \, or colon :.
The case-sensitivity of individual path components will vary based on operating system, or based on options specified at the time of a file system's creation or first use. In practice, this means that for a case-sensitive system, path components named component1 and Component1 can coexist at the same level in the hierarchy, whereas for a case-insensitive file system, they cannot (an error will occur). macOS and Windows' native file systems are case-insensitive by default, whereas typical Linux file systems are case-sensitive.
A path can be either relative or absolute. A relative path is a path in relation to another, most often the working directory. An absolute path indicates a location regardless of the current directory; that is, it specifies all path components starting from the file system's root, and does not depend on context like a relative path does.
Paths are also essential for locating hierarchically-organized network resources, as seen in URLs and UNC paths.

## Related

- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block availability map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Path_(computing)