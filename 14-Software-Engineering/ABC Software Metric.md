---
title: "ABC Software Metric"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/ABC_Software_Metric"
wikipedia_categories: ["Software metrics"]
related: ["[[Bauhaus Project (computing)]]", "[[Cockburn Scale]]", "[[Code coverage]]", "[[Cohesion (computer science)]]", "[[COSMIC functional size measurement]]", "[[Coupling (computer programming)]]", "[[Cppdepend]]", "[[Cyclomatic complexity]]", "[[Design predicates]]", "[[Domain-to-range ratio]]"]
---

# ABC Software Metric

The ABC software metric was introduced by Jerry Fitzpatrick in 1997 to overcome the drawbacks of the LOC. 
The metric defines an ABC score as a triplet of values that represent the size of a set of source code statements. An ABC score is calculated by counting the number of assignments (A), number of branches (B), and number of conditionals (C) in a program. ABC score can be applied to individual methods, functions, classes, modules or files within a program.
ABC score is represented by a 3-D vector < Assignments (A), Branches (B), Conditionals (C) >. It can also be represented as a scalar value, which is the magnitude of the vector < Assignments (A), Branches (B), Conditionals (C) >, and is calculated as follows:

  
    
      
        
          |
        
        
          A
          B
          C
          v
          e
          c
          t
          o
          r
        
        
          |
        
        
          
            
              A
              
                2
              
            
            
              B
              
                2
              
            
            
              C
              
                2
              
            
          
        
      
    
    
  

By convention, an ABC magnitude value is rounded to the nearest tenth.

## Related

- [[Bauhaus Project (computing)]]
- [[Cockburn Scale]]
- [[Code coverage]]
- [[Cohesion (computer science)]]
- [[COSMIC functional size measurement]]
- [[Coupling (computer programming)]]
- [[Cppdepend]]
- [[Cyclomatic complexity]]
- [[Design predicates]]
- [[Domain-to-range ratio]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ABC_Software_Metric