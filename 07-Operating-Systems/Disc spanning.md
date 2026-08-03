---
title: "Disc spanning"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Disc_spanning"
wikipedia_categories: ["Computer file systems", "Optical computer storage", "Rotating disc computer storage media"]
related: ["[[Cylinder-head-sector]]", "[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]"]
---

# Disc spanning

Disc spanning is a feature of CD and DVD burning software that automatically spreads a large amount of data across multiple data discs if the data set's size exceeds the storage capacity of an individual blank disc. The advantage is that the user does not need to split up files and directories into two or more (blank disc sized) pieces by hand. The software may or may not support slicing a single large file in order to span it but all disc spanners can divide multiple files that are smaller than one blank disc's capacity across a number of discs.
Disc spanning works on CD media in a number of applications, but spanning on DVD media fails often. This lack of reliable DVD data disc spanning is odd, as disc spanning was used extensively on older 3.5" and 5.25" floppy discs. It is incorrect that every operating system can perform disc spanning on any media as a built in function.
Some disc spanning schemes include a small program to reassemble the data set into the same structure it had on the source machine. This program could be written to the first disc only, or to every disc in the set.
The use of disc spanning will in most cases make your files unreadable to the file-system. Therefore, you are bounded to use the same program later on to restore the data. Multiple users don't want to be bound to such solutions and use "Simple disc spanning" instead.
Simple disc spanning is a solution that groups the files into any media grouped based on size. There is one drawback with this system. Files that are bigger than the target media will not be burnt to the drive. It is simple but powerful and a simple calculation would be "How many CD/DVD/BD/HD DVDs does this bunch of files need?".
The simple grouping can be displayed like this

Disc1 -- (99%) [4,479MiB]
Directory
|
+--- Dir1
+--- File1

Disc2 -- (98%) [4,468MiB]
Directory
|
+--- Dir2
+--- File2

Disc3 -- (45%) [2,130MiB]
|
+--- Dir3
etc...

## Related

- [[Cylinder-head-sector]]
- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block availability map]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Disc_spanning