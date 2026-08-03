---
title: "File locking"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/File_locking"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# File locking

File locking is a mechanism that restricts access to a computer file, or to a region of a file, by allowing only one user or process to modify or delete it at a specific time, and preventing reading of the file while it's being modified or deleted.
Systems implement locking to prevent an interceding update scenario, which is an example of a race condition, by enforcing the serialization of update processes to any given file. The following example illustrates the interceding update problem:

Process A reads a customer record from a file containing account information, including the customer's account balance and phone number.
Process B now reads the same record from the same file, so it has its own copy.
Process A changes the account balance in its copy of the customer record and writes the record back to the file.
Process B, which still has the original stale value for the account balance in its copy of the customer record, updates the account balance and writes the customer record back to the file.
Process B has now written its stale account-balance value to the file, causing the changes made by process A to be lost.
Most operating systems support the concept of record locking, which means that individual records within any given file may be locked, thereby increasing the number of concurrent update processes. Database maintenance uses file locking, whereby it can serialize access to the entire physical file underlying a database. Although this does prevent any other process from accessing the file, it can be more efficient than individually locking many regions in the file by removing the overhead of acquiring and releasing each lock.
Poor use of file locks, like any computer lock, can result in poor performance or in deadlocks. File locking may also refer to additional security applied by a computer user either by using Windows security, NTFS permissions or by installing a third party file locking software.

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

- Wikipedia: https://en.wikipedia.org/wiki/File_locking