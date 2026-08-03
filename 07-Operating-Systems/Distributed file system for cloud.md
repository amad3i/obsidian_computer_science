---
title: "Distributed file system for cloud"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_file_system_for_cloud"
wikipedia_categories: ["Cloud computing", "Cloud storage"]
related: ["[[Alibaba Cloud]]", "[[Cloud Foundry]]", "[[Cooperative storage cloud]]", "[[Kubity]]", "[[Microsoft Azure]]", "[[Nextcloud]]", "[[OpenIO]]", "[[Oracle Cloud]]", "[[Pydio]]", "[[Rclone]]"]
---

# Distributed file system for cloud

A distributed file system for cloud is a file system that allows many clients to have access to data and supports operations (create, delete, modify, read, write) on that data. Each data file may be partitioned into several parts called chunks. Each chunk may be stored on different remote machines, facilitating the parallel execution of applications. Typically, data is stored in files in a hierarchical tree, where the nodes represent directories. There are several ways to share files in a distributed architecture: each solution must be suitable for a certain type of application, depending on how complex the application is. Meanwhile, the security of the system must be ensured. Confidentiality, availability and integrity are the main keys for a secure system.
Users can share computing resources through the Internet thanks to cloud computing which is typically characterized by scalable and elastic resources – such as physical servers, applications and any services that are virtualized and allocated dynamically. Synchronization is required to make sure that all devices are up-to-date.
Distributed file systems enable many big, medium, and small enterprises to store and access their remote data as they do local data, facilitating the use of variable resources.

## Related

- [[Alibaba Cloud]]
- [[Cloud Foundry]]
- [[Cooperative storage cloud]]
- [[Kubity]]
- [[Microsoft Azure]]
- [[Nextcloud]]
- [[OpenIO]]
- [[Oracle Cloud]]
- [[Pydio]]
- [[Rclone]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_file_system_for_cloud