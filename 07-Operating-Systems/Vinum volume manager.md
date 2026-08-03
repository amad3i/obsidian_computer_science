---
title: "Vinum volume manager"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Vinum_volume_manager"
wikipedia_categories: ["BSD software", "Computer data storage", "DragonFly BSD", "FreeBSD", "Operating system technology", "RAID", "Rotating disc computer storage media", "Storage software"]
related: ["[[ALTQ]]", "[[Busdma]]", "[[Kqueue]]", "[[FreeBSD jail]]", "[[Soft updates]]", "[[Sysctl]]", "[[Vkernel]]", "[[Pfsync]]", "[[Single-instance storage]]", "[[Application binary interface]]"]
---

# Vinum volume manager

Vinum is a logical volume manager, also called software RAID, allowing implementations of the RAID-0, RAID-1 and RAID-5 models, both individually and in combination. The original Vinum was part of the base distribution of the FreeBSD operating system since 3.0, and also NetBSD between 2003-10-10 and 2006-02-25, as well as descendants of FreeBSD, including DragonFly BSD; in more recent versions of FreeBSD, it has been replaced with gvinum, which was first introduced around FreeBSD 6. Vinum source code is maintained in the FreeBSD and DragonFly source trees. Vinum supports RAID levels 0, 1, 5, and JBOD. Vinum was inspired by Veritas Volume Manager.
Vinum is invoked as gvinum (GEOM Vinum) on FreeBSD version 5.4 and up.
In modern FreeBSD, it may be considered to be a legacy volume manager; modern alternatives being GEOM and ZFS.
In NetBSD, it has been removed before NetBSD 4.0 due to lack of interest and maintenance; RAIDframe was cited as providing similar functionality.
In DragonFly BSD, DragonFly's own HAMMER filesystem already implements network mirroring, and the natacontrol utility could be used to configure nataraid(4), another software RAID implementation, which originally appeared with FreeBSD 6.0 as ataraid(4), but was deprecated with FreeBSD 9, and removed before FreeBSD 10.0; and a NetBSD's port of Red Hat's lvm2 is also available in the base system of DragonFly as well all in addition to vinum.

## Related

- [[ALTQ]]
- [[Busdma]]
- [[Kqueue]]
- [[FreeBSD jail]]
- [[Soft updates]]
- [[Sysctl]]
- [[Vkernel]]
- [[Pfsync]]
- [[Single-instance storage]]
- [[Application binary interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vinum_volume_manager