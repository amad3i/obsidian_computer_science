---
title: "Dancing tree"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Dancing_tree"
wikipedia_categories: ["B-tree", "Computer file systems", "Computer storage stubs"]
related: ["[[Allocate-on-flush]]", "[[Block allocation map]]", "[[Write Ahead Physical Block Logging]]", "[[Access method]]", "[[Aperture (computer memory)]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[B-tree]]"]
---

# Dancing tree

In computer science, a dancing tree is a tree data structure similar to B+ trees. It was invented by Hans Reiser, for use by the Reiser4 file system.  As opposed to self-balancing binary search trees that attempt to keep their nodes balanced at all times, dancing trees only balance their nodes when flushing data to a disk (either because of memory constraints or because a transaction has completed).
The idea behind this is to speed up file system operations by delaying optimization of the tree and only writing to disk when necessary, as writing to disk is thousands of times slower than writing to memory.  Also, because this optimization is done less often than with other tree data structures, the optimization can be more extensive.
In some sense, this can be considered to be a self-balancing binary search tree that is optimized for storage on a slow medium, in that the on-disc form will always be balanced but will get no mid-transaction writes; doing so eases the difficulty of adding and removing nodes during a transaction.  Instead, these slow rebalancing operations are performed at the same time as the much slower write to the storage medium.
However, a negative side effect of this behavior manifests in cases of unexpected shutdown, incomplete data writes, and other occurrences that may prevent the final balanced transaction from completing. In general, dancing trees pose greater difficulty than conventional trees for data recovery from incomplete transactions, though this can be addressed by more thoroughly accounting for transacted data.

## Related

- [[Allocate-on-flush]]
- [[Block allocation map]]
- [[Write Ahead Physical Block Logging]]
- [[Access method]]
- [[Aperture (computer memory)]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[B-tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dancing_tree