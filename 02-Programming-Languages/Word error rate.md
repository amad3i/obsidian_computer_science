---
title: "Word error rate"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Word_error_rate"
wikipedia_categories: ["Evaluation of machine translation", "Machine translation", "Rates", "Speech recognition"]
related: ["[[Apptek]]", "[[Cache language model]]", "[[Indic computing]]", "[[Linguatec]]", "[[ACL Data Collection Initiative]]", "[[Acoustic model]]", "[[Articulatory speech recognition]]", "[[Artificial intelligence content detection]]", "[[Audio mining]]", "[[Audio-visual speech recognition]]"]
---

# Word error rate

Word error rate (WER) is a common metric of the performance of a speech recognition or machine translation system. The WER metric typically ranges from 0 to 1, where 0 indicates that the compared pieces of text are exactly identical, and 1 (or larger) indicates that they are completely different with no similarity. This way, a WER of 0.8 means that there is an 80% error rate for compared sentences.
The general difficulty of measuring performance lies in the fact that the recognized word sequence can have a different length from the reference word sequence (supposedly the correct one). The WER is derived from the Levenshtein distance, working at the word level instead of the phoneme level. The WER is a valuable tool for comparing different systems as well as for evaluating improvements within one system. This kind of measurement, however, provides no details on the nature of translation errors and further work is therefore required to identify the main source(s) of error and to focus any research effort.
This problem is solved by first aligning the recognized word sequence with the reference (spoken) word sequence using dynamic string alignment. Examination of this issue is seen through a theory called the power law that states the correlation between perplexity and word error rate.
Word error rate can then be computed as:

  
    
      
        
          
            W
            E
            R
          
        
        
          
            
              S
              D
              I
            
            N
          
        
        
          
            
              S
              D
              I
            
            
              S
              D
              C
            
          
        
      
    
    
  

where

S is the number of substitutions,
D is the number of deletions,
I is the number of insertions,
C is the number of correct words,
N is the number of words in the reference (N=S+D+C)
The intuition behind 'deletion' and 'insertion' is how to get from the reference to the hypothesis. So if we have the reference "This is wikipedia" and hypothesis "This _ wikipedia", we call it a deletion.
Note that since N is the number of words in the reference, the word error rate can be larger than 1.0, namely if the number of insertions I is larger than the number of correct words C.
When reporting the performance of a speech recognition system, sometimes word accuracy (WAcc) is used instead:

  
    
      
        
          
            W
            A
            c
            c
          
        
        1
        
          
            W
            E
            R
          
        
        
          
            
              N
              S
              D
              I
            
            N
          
        
        
          
            
              C
              I
            
            N
          
        
      
    
    
  

Since the WER can be larger than 1.0, the word accuracy can be smaller than 0.0.

## Related

- [[Apptek]]
- [[Cache language model]]
- [[Indic computing]]
- [[Linguatec]]
- [[ACL Data Collection Initiative]]
- [[Acoustic model]]
- [[Articulatory speech recognition]]
- [[Artificial intelligence content detection]]
- [[Audio mining]]
- [[Audio-visual speech recognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Word_error_rate