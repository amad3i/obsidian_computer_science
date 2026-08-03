---
title: "Allocate-on-flush"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Allocate-on-flush"
wikipedia_categories: ["Computer file systems", "Computer storage stubs"]
related: ["[[Block allocation map]]", "[[Dancing tree]]", "[[Write Ahead Physical Block Logging]]", "[[Access method]]", "[[Aperture (computer memory)]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]"]
---

# Allocate-on-flush

Allocate-on-flush (also called delayed allocation) is a file system feature implemented in HFS+, XFS, Reiser4, ZFS, Btrfs, and ext4. The feature also closely resembles an older technique that Berkeley's UFS called "block reallocation".
When blocks must be allocated to hold pending writes, disk space for the appended data is subtracted from the free-space counter, but not actually allocated in the free-space bitmap. Instead, the appended data are held in memory until they must be flushed to storage due to memory pressure, when the kernel decides to flush dirty buffers, or when the application performs the Unix sync system call, for example.
This has the effect of batching together allocations into larger runs. Such delayed processing reduces CPU usage, and tends to reduce disk fragmentation, especially for files which grow slowly. It can also help in keeping allocations contiguous when there are several files growing at the same time.  When used in conjunction with copy-on-write as it is in ZFS, it can convert slow random writes into fast sequential writes.

## Related

- [[Block allocation map]]
- [[Dancing tree]]
- [[Write Ahead Physical Block Logging]]
- [[Access method]]
- [[Aperture (computer memory)]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Allocate-on-flush