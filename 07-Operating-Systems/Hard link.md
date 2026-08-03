---
title: "Hard link"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Hard_link"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Hard link

In computing, a hard link is a directory entry (in a directory-based file system) that associates a name with a file. Thus, each file must have at least one hard link. Creating additional hard links for a file makes the contents of that file accessible via additional paths (i.e., via different names or in different directories). This causes an alias effect: a process can open the file by any one of its paths and change its content. By contrast, a soft link or “shortcut” to a file is not a direct link to the data itself, but rather a reference to a hard link or another soft link.
Every directory is itself a special file on many systems, containing a list of file names instead of other data. Hence, multiple hard links to directories are possible, which could create a circular directory structure, rather than a branching structure like a tree. For that reason, some file systems forbid the creation of additional hard links to directories.
POSIX-compliant operating systems, such as Linux, Android, macOS, and the non-POSIX-compliant Windows NT family, support multiple hard links to the same file, depending on the file system. For instance, NTFS and ReFS support hard links, while FAT does not.

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

- Wikipedia: https://en.wikipedia.org/wiki/Hard_link