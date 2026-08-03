---
title: "Operating system abstraction layer"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Operating_system_abstraction_layer"
wikipedia_categories: ["Operating system technology"]
related: ["[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Busdma]]", "[[Chain loading]]", "[[Computer multitasking]]", "[[Computer terminal]]"]
---

# Operating system abstraction layer

An operating system abstraction layer (OSAL) provides an application programming interface (API) to an abstract operating system making it easier and quicker to develop code for multiple software or hardware platforms. It can make an application less dependent on any one specific operating system.
OS abstraction layers deal with presenting an abstraction of the common system functionality that is offered by any operating system by the means of providing meaningful and easy to use wrapper functions that in turn encapsulate the system functions offered by the OS to which the code needs porting.  A well designed OSAL provides implementations of an API for several real-time operating systems (such as vxWorks, eCos, RTLinux, RTEMS). Implementations may also be provided for non real-time operating systems, allowing the abstracted software to be developed and tested in a developer friendly desktop environment. 
In addition to the OS APIs, the OS abstraction layer project may also provide a hardware abstraction layer, designed to provide a portable interface to hardware devices such as memory, I/O ports, and non-volatile memory. To facilitate the use of these APIs, OSALs generally include a directory structure and build automation (e.g., set of makefiles) to facilitate building a project for a particular OS and hardware platform.
Implementing projects using OSALs allows for development of portable embedded system software that is independent of a particular real-time operating system. It also allows for embedded system software to be developed and tested on desktop workstations, providing a shorter development and debug time.

## Related

- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Busdma]]
- [[Chain loading]]
- [[Computer multitasking]]
- [[Computer terminal]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Operating_system_abstraction_layer