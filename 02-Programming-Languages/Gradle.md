---
title: "Gradle"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Gradle"
wikipedia_categories: ["2007 software", "Build automation", "Compiling tools", "Cross-platform software", "Java development tools", "Software using the Apache license"]
related: ["[[Apache Ant]]", "[[Apache Maven]]", "[[Apache CouchDB]]", "[[Apache Groovy]]", "[[ArkTS]]", "[[Azure DevOps Server]]", "[[Clojure]]", "[[Crystal (programming language)]]", "[[Mojo (programming language)]]", "[[Open Inventor]]"]
---

# Gradle

Gradle Build Tool ("Gradle") is a build automation tool for multi-language software development produced by Gradle Technologies. It manages tasks like compilation, packaging, testing, deployment, and publishing. Supported languages include Java (as well as JDK-based languages Kotlin, Groovy, Scala), C/C++, and JavaScript.
Gradle builds on the concepts of Apache Ant and Apache Maven, and introduces a Groovy- and Kotlin-based domain-specific language contrasted with the XML-based project configuration used by Maven. Gradle uses a directed acyclic graph to provide dependency management. The graph is used to determine the order in which tasks should be executed. Gradle runs on the Java Virtual Machine.
Gradle was designed for multi-project builds, which can grow to be large. It operates based on a series of build tasks that can run serially or in parallel. Incremental builds are supported by determining the parts of the build tree that are already up to date; any task dependent only on those parts does not need to be re-executed. It also supports caching of build components, potentially across a shared network using the Gradle Build Cache. Combined with the proprietary hosted service of Develocity, it produces web-based build visualizations called Gradle Build Scans. The software is extensible for new features and programming languages with a plugin subsystem.
Gradle is distributed as Free Software under the Apache License 2.0, and was first released in 2008.

## Related

- [[Apache Ant]]
- [[Apache Maven]]
- [[Apache CouchDB]]
- [[Apache Groovy]]
- [[ArkTS]]
- [[Azure DevOps Server]]
- [[Clojure]]
- [[Crystal (programming language)]]
- [[Mojo (programming language)]]
- [[Open Inventor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gradle