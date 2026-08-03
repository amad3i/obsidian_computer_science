---
title: "Modules (C++)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Modules_(C++)"
wikipedia_categories: []
related: []
---

# Modules (C++)

Modules in C++ are a feature added in C++20 implementing modular programming as a modern alternative to precompiled headers. A module in C++ comprises a single translation unit. Like header files and implementation files, a module can contain declarations and definitions, but differ from precompiled headers in that they do not require the preprocessor directive #include, but rather are accessed using the word import. A module must be declared using the word module to indicate that the translation unit is a module. A module, once compiled, is stored as a built module interface (BMI) file which acts very similar to a .pch (precompiled header) file. Module symbols and imports are resolved at the compilation stage, not the linking stage.
Modules most commonly have the extension .cppm (primarily common within Clang and GCC toolchains), though some alternative extensions include .ixx and .mxx (more common in Microsoft/MSVC toolchains), or even the traditional C++ extension .cpp.
Though the standard C language does not have modules, dialects of C allow for modules, such as Clang C. However, the syntax and semantics of Clang C modules differ from C++ modules significantly.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Modules_(C++)