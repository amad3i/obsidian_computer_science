---
title: "Global file system"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Global_file_system"
wikipedia_categories: ["Computer file systems", "Distributed computing"]
related: ["[[Access method]]", "[[ActivityPub]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Basic partitioned access method]]"]
---

# Global file system

In computer storage, a global file system is a distributed file system that can be accessed from multiple locations, typically across a wide-area network, and provides concurrent access to a global namespace from all locations. In order for a file system to be considered global, it must allow for files to be created, modified, and deleted from any location. This access is typically provided by a cloud storage gateway at each edge location, which provides access using the NFS or SMB network file sharing protocols.
There are a number of benefits to using a global file system. First, global file systems can improve the availability of data by allowing multiple copies to be stored in different locations, as well as allowing for rapid restoration of lost data from a remote location. This can be helpful in the event of a disaster, such as a power outage or a natural disaster. Second, global file systems can improve performance by allowing data to be cached closer to the users who are accessing it. This can be especially beneficial in cases where data is accessed by users in different parts of the world. Finally, in contrast to traditional Network attached storage, global file systems can improve the ability of users to collaborate across multiple sites, in a manner similar to Enterprise file synchronization and sharing.

## Related

- [[Access method]]
- [[ActivityPub]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Basic partitioned access method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Global_file_system