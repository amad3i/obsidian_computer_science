---
title: "Collaborative human interpreter"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Collaborative_human_interpreter"
wikipedia_categories: ["Domain-specific programming languages", "Human-based computation"]
related: ["[[Apple Media Tool]]", "[[APT (programming language)]]", "[[AWK]]", "[[Bash (Unix shell)]]", "[[Bayesian inference using Gibbs sampling]]", "[[BEFLIX]]", "[[CAPTCHA]]", "[[CLIPS]]", "[[ColdFusion Markup Language]]", "[[Compiler-compiler]]"]
---

# Collaborative human interpreter

The collaborative human interpreter (CHI) is a proposed software interface for human-based computation (first proposed as a programming language on the blog Google Blogoscoped, but implementable via an API in virtually any programming language) specially designed for collecting 
and making use of human intelligence in a computer program.
One typical usage is implementing impossible-to-automate functions.
For example, it is currently difficult for a computer to differentiate between images of men, women and non-humans. However, this is easy for people. A programmer using CHI could write a code fragment along these lines:

enum GenderCode {
 MALE, FEMALE, NOT_A_HUMAN 
}
Photo photo = loadPhoto(file)
GenderCode result = checkGender(photo)

Code for the function checkGender(Photo p) can currently only approximate a result, but the task can easily be solved by a person. When the function checkGender() is called, the system will send a request to someone, and the person who received the request will process the task and input the result. If the person (task processor) inputs value MALE, you'll get the value in your variable result, in your program. This querying process can be highly automated.

## Related

- [[Apple Media Tool]]
- [[APT (programming language)]]
- [[AWK]]
- [[Bash (Unix shell)]]
- [[Bayesian inference using Gibbs sampling]]
- [[BEFLIX]]
- [[CAPTCHA]]
- [[CLIPS]]
- [[ColdFusion Markup Language]]
- [[Compiler-compiler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Collaborative_human_interpreter