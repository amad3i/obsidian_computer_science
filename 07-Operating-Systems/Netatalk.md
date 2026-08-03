---
title: "Netatalk"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Netatalk"
wikipedia_categories: ["Apple II software", "Free software programmed in C", "MacOS software", "Network protocols", "Software that uses Meson", "Software using the GNU General Public License"]
related: ["[[Bash (Unix shell)]]", "[[Concurrent Versions System]]", "[[Git]]", "[[IF-MAP]]", "[[KornShell]]", "[[Linux kernel]]", "[[Linux-libre]]", "[[Mercurial]]", "[[Miredo]]", "[[Privoxy]]"]
---

# Netatalk

Netatalk (pronounced "ned-uh-talk") is a free, open-source implementation of the Apple Filing Protocol (AFP). It allows Unix-like operating systems to serve as file servers for Macintosh computers running macOS or Classic Mac OS, or any computer with a 3rd party AFP client.
Netatalk was originally developed by the Research Systems Unix Group at the University of Michigan for BSD-derived Unix systems and released in 1990. Apple had introduced AppleTalk soon after the release of the original Macintosh in 1985, followed by the file sharing application AppleShare (which was built on top of AFP) in 1987. This was an early example of zero-configuration networking, gaining significant adoption in educational and small to mid size office environments in the late 80s. Netatalk emerged as a part of the software ecosystem around AppleTalk.
In 1986, Columbia University published the Columbia AppleTalk Package (CAP), which was an open source implementation of AppleTalk originally written for BSD 4.2, allowing Unix servers to be part of AppleTalk networks. CAP also had its own implementation of AFP/AppleShare, but Netatalk appearing in 1990 claimed better performance due to software design advantages. CAP and Netatalk were also interoperable, the latter being able to be run on an AppleTalk backend provided by CAP.
Since Classic Mac OS uses a forked file system, unlike the host operating systems where Netatalk would be running, Netatalk originally implemented the AppleDouble format for storing the resource fork separately from the data fork when a Mac OS file was transferred to the Unix-like computer's file system. This was required in order not to ruin most files by discarding the resource fork when copied to the Netatalk served AppleShare volume. With the release of Netatalk 3.0, the backend was re-implemented to use the Extended Attributes format that Apple had introduced with Mac OS X for backwards compatibility with Classic Mac OS resource forks.

## Related

- [[Bash (Unix shell)]]
- [[Concurrent Versions System]]
- [[Git]]
- [[IF-MAP]]
- [[KornShell]]
- [[Linux kernel]]
- [[Linux-libre]]
- [[Mercurial]]
- [[Miredo]]
- [[Privoxy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Netatalk