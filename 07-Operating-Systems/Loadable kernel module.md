---
title: "Loadable kernel module"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Loadable_kernel_module"
wikipedia_categories: ["Device drivers", "FreeBSD", "Linux kernel", "Operating system kernels"]
related: ["[[Linux-libre]]", "[[ALTQ]]", "[[Board support package]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Busdma]]", "[[CEN-XFS]]", "[[Configuration Menu Language]]", "[[Copy Fail]]"]
---

# Loadable kernel module

A loadable kernel module (LKM) is an executable library that extends the capabilities of a running kernel, or so-called base kernel, of an operating system. LKMs are typically used to add support for new hardware (as device drivers) and/or filesystems, or for adding system calls. When the functionality provided by an LKM is no longer required, it can be unloaded in order to free memory and other resources.
Most current Unix-like systems and Windows support loadable kernel modules but with different names, such as kernel loadable module (kld) in FreeBSD, kernel extension (kext) in macOS (although support for third-party modules is being dropped), kernel extension module in AIX, dynamically loadable kernel module in HP-UX, kernel-mode driver in Windows NT  and downloadable kernel module (DKM) in VxWorks. They are also known as kernel loadable module (KLM), or simply as kernel module (KMOD).

## Related

- [[Linux-libre]]
- [[ALTQ]]
- [[Board support package]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Busdma]]
- [[CEN-XFS]]
- [[Configuration Menu Language]]
- [[Copy Fail]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Loadable_kernel_module