---
title: "Frequency scaling"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Frequency_scaling"
wikipedia_categories: ["Central processing unit", "Computer architecture"]
related: ["[[Arithmetic logic unit]]", "[[Byte addressing]]", "[[Computer architecture]]", "[[Processor register]]", "[[Simultaneous multithreading]]", "[[Temporal multithreading]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]"]
---

# Frequency scaling

In computer architecture, frequency scaling (also known as frequency ramping) is the technique of increasing a processor's frequency so as to enhance the performance of the system containing the processor in question. Frequency ramping was the dominant force in commodity processor performance increases from the mid-1980s until roughly the end of 2004. 
The effect of processor frequency on computer speed can be seen by looking at the equation for computer program runtime: 

  
    
      
        
          R
          u
          n
          t
          i
          m
          e
        
        
          
            
              I
              n
              s
              t
              r
              u
              c
              t
              i
              o
              n
              s
            
            
              P
              r
              o
              g
              r
              a
              m
            
          
        
        
          
            
              C
              y
              c
              l
              e
              s
            
            
              I
              n
              s
              t
              r
              u
              c
              t
              i
              o
              n
            
          
        
        
          
            
              T
              i
              m
              e
            
            
              C
              y
              c
              l
              e
            
          
        
        ,
      
    
    
  

where instructions per program is the total instructions being executed in a given program, cycles per instruction is a program-dependent, architecture-dependent average value, and time per cycle is by definition the inverse of processor frequency. An increase in frequency thus decreases runtime. 
However, power consumption in a chip is given by the equation 

  
    
      
        P
        C
        
          V
          
            2
          
        
        F
        ,
      
    
    
  

where P is power consumption, C is the capacitance being switched per clock cycle, V is voltage, and F is the processor frequency (cycles per second). Increases in frequency thus increase the amount of power used in a processor. Increasing processor power consumption led ultimately to Intel's May 2004 cancellation of its Tejas and Jayhawk processors, which is generally cited as the end of frequency scaling as the dominant computer architecture paradigm. 
Moore's Law was still in effect when frequency scaling ended. Despite power issues, transistor densities were still doubling every 18 to 24 months. With the end of frequency scaling, new transistors (which are no longer needed to facilitate frequency scaling) are used to add extra hardware, such as additional cores, to facilitate parallel computing - a technique that is being referred to as parallel scaling.
The end of frequency scaling as the dominant cause of processor performance gains has caused an industry-wide shift to parallel computing in the form of multicore processors.

## Related

- [[Arithmetic logic unit]]
- [[Byte addressing]]
- [[Computer architecture]]
- [[Processor register]]
- [[Simultaneous multithreading]]
- [[Temporal multithreading]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Frequency_scaling