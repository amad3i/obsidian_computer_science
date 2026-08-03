---
title: "IBM DevOps Code ClearCase"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/IBM_DevOps_Code_ClearCase"
wikipedia_categories: ["Collaborative software", "Computer-aided software engineering tools", "Concurrent Versions System", "Proprietary version control systems", "Rational Software software", "Software that uses Motif (software)"]
related: ["[[Apache Subversion]]", "[[Azure DevOps Server]]", "[[Academic Torrents]]", "[[Adobe Story]]", "[[ApexKB]]", "[[Architecture of Interoperable Information Systems]]", "[[Asana, Inc]]", "[[Binder Project]]", "[[BookStack]]", "[[Business interoperability interface]]"]
---

# IBM DevOps Code ClearCase

IBM DevOps Code ClearCase (also known as IBM Rational ClearCase) is a family of computer software tools that supports software configuration management (SCM) of source code and other software development assets. It also supports design-data management of electronic design artifacts, thus enabling hardware and software co-development. ClearCase includes revision control and forms the basis for configuration management at large and medium-sized businesses, accommodating projects with hundreds or thousands of developers. It is developed by IBM.
ClearCase supports two configuration management models: UCM (Unified Change Management) and base ClearCase. UCM provides an out-of-the-box model while base ClearCase provides a basic infrastructure (UCM is built on base ClearCase). Both can be customized to support a wide variety of needs.
ClearCase can accommodate large binary files, a large number of files, and large repository sizes. It supports branching and labeling. It enables the correct merging of refactored files by versioning directories. It also supports extensive process automation and enforcement using triggers, attributes, hyperlinks, and other metadata. It uses the MultiVersion File System (MVFS), which is a virtual file system that transparently determines which versions of files and directories should be in the workspace and orchestrates file access and lifecycle. The MVFS is used in LAN deployments for dynamic views and in LAN or WAN deployments for automatic views.
ClearCase also provides authoritative build auditing, which generates metadata for each build artifact, including the context of the build and a bill of materials of files (including the exact version) referenced during the build. This metadata can be used for generating SBOMs (Software Bill of Materials) and is important in regulated environments where artifact traceability is essential. ClearCase includes an implementation of 'make' that integrates with the authoritative build auditing mechanism to ensure build correctness without timestamps and automatic sharing of build artifacts across views (workspaces).

## Related

- [[Apache Subversion]]
- [[Azure DevOps Server]]
- [[Academic Torrents]]
- [[Adobe Story]]
- [[ApexKB]]
- [[Architecture of Interoperable Information Systems]]
- [[Asana, Inc]]
- [[Binder Project]]
- [[BookStack]]
- [[Business interoperability interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IBM_DevOps_Code_ClearCase