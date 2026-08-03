---
title: "Mode setting"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Mode_setting"
wikipedia_categories: ["Device drivers", "Graphics hardware", "Operating system technology"]
related: ["[[Hardware abstraction]]", "[[Network redirector]]", "[[User space and kernel space]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Board support package]]"]
---

# Mode setting

Mode setting is a software operation that activates a display mode (screen resolution, color depth, and refresh rate) for a computer's display controller by using VESA BIOS Extensions or UEFI Graphics extensions (on more modern computers).
The display mode is set by the kernel. In user-space mode-setting (UMS), the display mode is set by a user-space process.
Kernel mode-setting is more flexible and allows displaying of an error in the case of a fatal system error in the kernel, even when using a user-space display server.
User-space mode setting would require superuser privileges for direct hardware access, so kernel-based mode setting shuns such requirement for the user-space graphics server.
On the hardware side, the GPU consists of multiple components, among which are render engine, i.e. the component of the GPU responsible for executing OpenGL/Vulkan commands, and the display engine, i.e. the component of the GPU responsible for sending a "video stream" to the screen, as opposed to the part performing rendering.
To improve performance, many GPUs come with a feature called hardware planes. Planes can make the display engine perform the composition. This is called direct scan-out and allows the compositor to avoid copying entirely. libliftoff is a library making better use of such hardware ability.

## Related

- [[Hardware abstraction]]
- [[Network redirector]]
- [[User space and kernel space]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Board support package]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mode_setting