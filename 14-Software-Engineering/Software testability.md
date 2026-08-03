---
title: "Software testability"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Software_testability"
wikipedia_categories: ["Software quality", "Software testing"]
related: ["[[Business process validation]]", "[[Flaky test]]", "[[List of software bugs]]", "[[Process validation]]", "[[Reverse semantic traceability]]", "[[Self-healing test automation]]", "[[Software map]]", "[[Software quality]]", "[[-dev-full]]", "[[A-B testing]]"]
---

# Software testability

Software testability is the degree to which a software artifact (e.g. a software system, module, requirement, or design document) supports testing in a given test context. If the testability of an artifact is high, then finding faults in the system (if any) by means of testing is easier.
Formally, some systems are testable, and some are not. This classification can be achieved by noticing that, to be testable, for a functionality of the system under test "S", which takes input "I", a computable functional predicate "V" must exists such that 
  
    
      
        V
        S
        ,
        I
      
    
    
  
 is true when S, given input I, produce a valid output, false otherwise. This function "V" is known as the verification function for the system with input I.
Many software systems are untestable, or not immediately testable. For example, Google's ReCAPTCHA, without having any metadata about the images is not a testable system. Recaptcha, however, can be immediately tested if for each image shown, there is a tag stored elsewhere. Given this meta information, one can test the system.
Therefore, testability is often thought of as an extrinsic property which results from interdependency of the software to be tested and the test goals, test methods used, and test resources (i.e., the test context). Even though testability can not be measured directly (such as software size) it should be considered an intrinsic property of a software artifact because it is highly correlated with other key software qualities such as encapsulation, coupling, cohesion, and redundancy.
The correlation of 'testability' to good design can be observed by seeing that code that has weak cohesion, tight coupling, redundancy and lack of encapsulation is difficult to test.
A lower degree of testability results in increased test effort. In extreme cases a lack of testability may hinder testing parts of the software or software requirements at all.

## Related

- [[Business process validation]]
- [[Flaky test]]
- [[List of software bugs]]
- [[Process validation]]
- [[Reverse semantic traceability]]
- [[Self-healing test automation]]
- [[Software map]]
- [[Software quality]]
- [[-dev-full]]
- [[A-B testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Software_testability