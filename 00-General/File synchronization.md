---
title: "File synchronization"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/File_synchronization"
wikipedia_categories: ["Data synchronization", "Storage software", "Utility software types"]
related: ["[[Compensating transaction]]", "[[Compiler]]", "[[Decompiler]]", "[[Digital calendar]]", "[[File archiver]]", "[[Filecoin]]", "[[Kopano (software)]]", "[[Linker (computing)]]", "[[Log shipping]]", "[[Novell File Reporter]]"]
---

# File synchronization

File synchronization (or syncing) in computing is the process of ensuring that computer files in two or more locations are updated via certain rules.
In one-way file synchronization, also called mirroring, updated files are copied from a source location to one or more target locations, but no files are copied back to the source location. In two-way file synchronization, updated files are copied in both directions, usually with the purpose of keeping the two locations identical to each other. In this article, the term synchronization refers exclusively to two-way file synchronization.
File synchronization is commonly used for home backups on external hard drives or updating for transport on USB flash drives. BitTorrent Sync, Dropbox, SKYSITE, Nextcloud, OneDrive, Google Drive and iCloud are prominent products. Some backup software also supports real-time file sync. The automatic process prevents copying already identical files and thus can be faster and save much time versus a manual copy, and is less error prone. However this suffers from the limit that the synchronized files must physically fit in the portable storage device. Synchronization software that only keeps a list of files and the changed files eliminates this problem (e.g. the "snapshot" feature in Beyond Compare or the "package" feature in Synchronize It!). It is especially useful for mobile workers, or others that work on multiple computers.
It is possible to synchronize multiple locations by synchronizing them one pair at a time. The Unison Manual describes how to do this:

If you need to do this, the most reliable way to set things up is to organize the machines into a "star topology," with one machine designated as the "hub" and the rest as "spokes," and with each spoke machine synchronizing only with the hub. The big advantage of the star topology is that it eliminates the possibility of confusing "spurious conflicts" arising from the fact that a separate archive is maintained by Unison for every pair of hosts that it synchronizes.

## Related

- [[Compensating transaction]]
- [[Compiler]]
- [[Decompiler]]
- [[Digital calendar]]
- [[File archiver]]
- [[Filecoin]]
- [[Kopano (software)]]
- [[Linker (computing)]]
- [[Log shipping]]
- [[Novell File Reporter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/File_synchronization