---
title: "Simple DirectMedia Layer"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer"
wikipedia_categories: ["Application programming interfaces", "Audio libraries", "C (programming language) libraries", "Cross-platform software", "Graphics libraries", "Linux APIs", "MacOS APIs", "Simple DirectMedia Layer"]
related: ["[[OpenGL]]", "[[Open Inventor]]", "[[OpenCL]]", "[[C (programming language)]]", "[[Glide (API)]]", "[[SYCL]]", "[[Ultimate++]]", "[[WebGL]]", "[[4th Dimension (software)]]", "[[A-Frame (software)]]"]
---

# Simple DirectMedia Layer

Simple DirectMedia Layer (SDL) is a cross-platform software development library designed to provide a hardware abstraction layer for computer multimedia hardware components. Software developers can use it to write high-performance computer games and other multimedia applications that can run on many operating systems such as AmigaOS, Android, iOS, Linux, MorphOS, macOS, and Windows.
SDL manages video, audio, input devices, threads, shared object loading, computer networking and timers. For 3D graphics, it can handle an OpenGL, Vulkan, Metal, or Direct3D12 (older Direct3D versions 11 and 9 are also supported) context. A common misconception is that SDL is a game engine. However, the library is suited to building games directly, or is usable indirectly by engines built on top of it.
The library is internally written in C and possibly, depending on the target platform, C++ or Objective-C, and provides the application programming interface in C, with bindings to other languages available. It is free and open-source software subject to the requirements of the zlib License since version 2.0, and with prior versions subject to the GNU Lesser General Public License. Under the zlib License, SDL 2.0 is freely available for static linking in closed-source projects, unlike SDL 1.2, although it is possible for the user to override the statically linked library with one provided by them. SDL 2.0, released in 2013, was a major departure from previous versions, offering more opportunity for 3D hardware acceleration, but breaking backwards-compatibility; a wrapper library made to translate 1.2 calls to 2.0 was later made available.
SDL is extensively used in the industry in both large and small projects. By 2010, over 700 games, 180 applications, and 120 demos had been posted on the library website.
SDL supports Emscripten (i.e. programs that run on a web page).
SDL 3 was released, as a stable version, in January 2025. It has a migration guide, and Coccinelle tool support to help migrate to the new major version. SDL 3 has a new way to control the entry point of your program, and you can optionally control execution in a non-framework way.

## Related

- [[OpenGL]]
- [[Open Inventor]]
- [[OpenCL]]
- [[C (programming language)]]
- [[Glide (API)]]
- [[SYCL]]
- [[Ultimate++]]
- [[WebGL]]
- [[4th Dimension (software)]]
- [[A-Frame (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer