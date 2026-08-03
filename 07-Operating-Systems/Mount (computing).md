---
title: "Mount (computing)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Mount_(computing)"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Mount (computing)

Mounting is a process by which a computer's operating system makes files and directories on a storage device (such as hard drive, CD-ROM, or network share) available for users to access via the computer's file system.
In general, the process of mounting comprises the operating system acquiring access to the storage medium; recognizing, reading, and processing file system structure and metadata on it before registering them to the virtual file system (VFS) component.
The location in the VFS to which the newly mounted medium was registered is called a mount point; when the mounting process is completed, the user can access files and directories on the medium from there.
An opposite process of mounting is called unmounting, in which the operating system cuts off all user access to files and directories on the mount point, writes the remaining queue of user data to the storage device, refreshes file system metadata, then relinquishes access to the device, making the storage device safe for removal.
Normally, when the computer is shutting down, every mounted storage device will undergo an unmounting process to ensure that all queued data was written to it, and to preserve the integrity of the file system structure on the media.

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

- Wikipedia: https://en.wikipedia.org/wiki/Mount_(computing)