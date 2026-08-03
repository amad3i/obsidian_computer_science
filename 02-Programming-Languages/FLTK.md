---
title: "FLTK"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/FLTK"
wikipedia_categories: ["Cross-platform free software", "FLTK", "Free computer libraries", "Free software programmed in C++", "Software that uses Cairo (graphics)", "Software using the GNU Lesser General Public License", "Widget toolkits", "X-based libraries"]
related: ["[[ARToolKit]]", "[[Processing]]", "[[Ultimate++]]", "[[ChatScript]]", "[[Collabora Online]]", "[[Dasher (software)]]", "[[DuckDB]]", "[[GNU Compiler Collection]]", "[[H2 Database Engine]]", "[[Lua]]"]
---

# FLTK

Fast Light Toolkit (FLTK) is a cross-platform widget (graphical control element) library for graphical user interfaces (GUIs), developed by Bill Spitzak and others. Made to accommodate 3D graphics programming, it has an interface to OpenGL, but it is also suitable for general GUI programming.
Using its own widget, drawing and event systems abstracted from the underlying system-dependent code, it allows for writing programs which look the same on all supported operating systems.
FLTK is free and open-source software, licensed under GNU Lesser General Public License (LGPL) with an added clause permitting static linking from applications with incompatible licenses.
In contrast to user interface libraries like GTK, Qt, and wxWidgets, FLTK uses a more lightweight design and restricts itself to GUI functionality. Because of this, the library is very small (the FLTK "Hello World" program is around 100 KiB), and is usually statically linked. It also avoids complex macros, separate code preprocessors, and use of some advanced C++ features: templates, exceptions, and run-time type information (RTTI) or, for FLTK 1.x, namespaces. Combined with the modest size of the package, this makes it relatively easy to learn for new users.
These advantages come with corresponding disadvantages. FLTK offers fewer widgets than most GUI toolkits and, because of its use of non-native widgets, does not have native look-and-feel on any platform.

## Related

- [[ARToolKit]]
- [[Processing]]
- [[Ultimate++]]
- [[ChatScript]]
- [[Collabora Online]]
- [[Dasher (software)]]
- [[DuckDB]]
- [[GNU Compiler Collection]]
- [[H2 Database Engine]]
- [[Lua]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FLTK