---
title: "Weissman score"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Weissman_score"
wikipedia_categories: ["Benchmarks (computing)", "Data compression", "Silicon Valley (TV series)", "Software metrics"]
related: ["[[ABC Software Metric]]", "[[Algorithmic qubits]]", "[[Bauhaus Project (computing)]]", "[[BGZF]]", "[[BogoMips]]", "[[BREACH]]", "[[Byte Sieve]]", "[[Canonical Huffman code]]", "[[Cockburn Scale]]", "[[Code coverage]]"]
---

# Weissman score

The Weissman score is a performance metric for lossless compression applications. It was developed by Tsachy Weissman, a professor at Stanford University, and Vinith Misra, a graduate student, at the request of producers for HBO's television series Silicon Valley, a television show about a fictional tech start-up working on a data compression algorithm. It compares both required time and compression ratio of measured applications, with those of a de facto standard according to the data type.
The formula is the following; where r is the compression ratio, T is the time required to compress, the overlined ones are the same metrics for a standard compressor, and alpha is a scaling constant.

  
    
      
        W
        α
        
          
            r
            
              
                r
                ¯
              
            
          
        
        
          
            
               
              
                
                  T
                  ¯
                
              
            
            
               
              
                T
              
            
          
        
      
    
    
  

The Weissman score has been used by Daniel Reiter Horn  and Mehant Baid of Dropbox to explain real-world work on lossless compression. According to the authors it "favors compression speed over ratio in most cases."

## Related

- [[ABC Software Metric]]
- [[Algorithmic qubits]]
- [[Bauhaus Project (computing)]]
- [[BGZF]]
- [[BogoMips]]
- [[BREACH]]
- [[Byte Sieve]]
- [[Canonical Huffman code]]
- [[Cockburn Scale]]
- [[Code coverage]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weissman_score