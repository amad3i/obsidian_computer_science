---
title: "Perl::Critic"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Perl::Critic"
wikipedia_categories: ["Perl", "Program analysis", "Static program analysis"]
related: ["[[Static program analysis]]", "[[Abstract interpretation]]", "[[ActivePerl]]", "[[Alias analysis]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Compiler-compiler]]", "[[Context-free language reachability]]"]
---

# Perl::Critic

Perl::Critic is a static code analysis system for the Perl programming language. Perl::Critic is available as a source-code distribution on CPAN. It comes with a commandline tool, perlcritic, which can check Perl source code files and report on the code quality therein. Perl::Critic has an extensible architecture that allows the programmer to choose from many "policies" which enforce different Perl programming styles and tastes. The default policy is largely based on the recommendations in the book Perl Best Practices by Damian Conway.
Perl::Critic is based on the PPI parsing library. For safety, PPI does not execute any code while parsing, unlike the Perl compiler, so it is a close approximation of the real parser rather than an exact representation.
Some new alternatives include Perl::Lint and B::Lint.

## Related

- [[Static program analysis]]
- [[Abstract interpretation]]
- [[ActivePerl]]
- [[Alias analysis]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Compiler-compiler]]
- [[Context-free language reachability]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Perl::Critic