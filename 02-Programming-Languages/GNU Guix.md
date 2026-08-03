---
title: "GNU Guix"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/GNU_Guix"
wikipedia_categories: ["2013 software", "Free package management systems", "Free software programmed in Lisp", "Functional programming", "GNU Project software", "Linux distributions without systemd", "Linux package management-related software", "Software using the GNU General Public License"]
related: ["[[Nix (package manager)]]", "[[Snap (software)]]", "[[Bash (Unix shell)]]", "[[DejaGnu]]", "[[Flatpak]]", "[[GNU Compiler Collection]]", "[[Linux-libre]]", "[[Prototype Verification System]]", "[[Revision Control System]]", "[[Tox (protocol)]]"]
---

# GNU Guix

GNU Guix (; portmanteau of Guile and Nix) is a functional programming cross-platform package manager and a tool to instantiate and manage Unix-like operating systems, inspired by the Nix package manager. Configuration and package recipes are written in Guile Scheme. GNU Guix is the default package manager of the GNU Guix System distribution.
Differing from traditional package managers, Guix (like Nix) uses a purely functional programming deployment model where software is installed into unique directories generated through cryptographic hash functions. All dependencies for each software are included in the input of each hash. This solves the problem of dependency hell, allowing multiple versions of the same software to coexist which makes packages portable and reproducible. Performing scientific computations in a Guix setup has been proposed as a promising response to the replication crisis.
The development of GNU Guix is intertwined with the GNU Guix System, an installable operating system distribution using the Linux-libre kernel and the GNU Shepherd init system.

## Related

- [[Nix (package manager)]]
- [[Snap (software)]]
- [[Bash (Unix shell)]]
- [[DejaGnu]]
- [[Flatpak]]
- [[GNU Compiler Collection]]
- [[Linux-libre]]
- [[Prototype Verification System]]
- [[Revision Control System]]
- [[Tox (protocol)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GNU_Guix