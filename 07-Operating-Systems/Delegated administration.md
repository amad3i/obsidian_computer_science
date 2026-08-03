---
title: "Delegated administration"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Delegated_administration"
wikipedia_categories: ["Active Directory", "Computer access control", "Decentralization", "Operating system technology"]
related: ["[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Authentication]]", "[[Authorization]]", "[[Binary Application Markup Language]]", "[[Busdma]]", "[[Chain loading]]"]
---

# Delegated administration

In computing, delegated administration or delegation of control describes the decentralization of role-based-access-control systems.  Many enterprises use a centralized model of access control.  For large organizations, this model scales poorly and IT teams become burdened with menial role-change requests.  These requests — often used when hire, fire, and role-change events occur in an organization — can incur high latency times or suffer from weak security practices.
Such delegation involves assigning a person or group specific administrative permissions for an Organizational Unit.  In information management, this is used to create teams that can perform specific (limited) tasks for changing information within a user directory or database.  The goal of delegation is to create groups with minimum permissions that grant the ability to carry out authorized tasks. Granting extraneous/superfluous permissions would create abilities beyond the authorized scope of work.
One best practice for enterprise role management entails the use of LDAP groups.  Delegated administration refers to a decentralized model of role or group management.  In this model, the application or process owner creates, manages and delegates the management of roles.  A centralized IT team simply operates the service of directory, metadirectory, web interface for administration, and related components.
Allowing the application or business process owner to create, manage and delegate groups supports a much more scalable approach to the administration of access rights.
In a metadirectory environment, these roles or groups could also be "pushed" or synchronized with other platforms.  For example, groups can be synchronized with native operating systems such as Microsoft Windows for use on an access control list that protects a folder or file.  With the metadirectory distributing groups, the central directory is the central repository of groups.
Some enterprise applications (e.g., PeopleSoft) support LDAP groups inherently.  These applications are capable of using LDAP to call the directory for its authorization activities.
Web-based group management tools — used for delegated administration — therefore provide the following capabilities using a directory as the group repository:

Decentralized management of groups (roles) and access rights by business- or process-owners
Categorizing or segmenting users by characteristic, not by enumeration
Grouping users for e-mail, subscription, and access control
Reducing work process around maintenance of groups
Reproducing groups on multiple platforms and into disparate environments

## Related

- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Authentication]]
- [[Authorization]]
- [[Binary Application Markup Language]]
- [[Busdma]]
- [[Chain loading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Delegated_administration