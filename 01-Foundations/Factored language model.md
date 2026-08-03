---
title: "Factored language model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Factored_language_model"
wikipedia_categories: ["Language modeling", "Natural language processing stubs", "Probabilistic models", "Statistical natural language processing"]
related: ["[[Probabilistic context-free grammar]]", "[[Brown clustering]]", "[[Katz's back-off model]]", "[[Language model]]", "[[Latent Dirichlet allocation]]", "[[Markov information source]]", "[[N-gram]]", "[[Natural Language Toolkit]]", "[[Pachinko allocation]]", "[[Probabilistic latent semantic analysis]]"]
---

# Factored language model

The factored language model (FLM) is an extension of a conventional language model introduced by Jeff Bilmes and Katrin Kirchoff in 2003.  In an FLM, each word is viewed as a vector of k factors: 
  
    
      
        
          w
          
            i
          
        
        {
        
          f
          
            i
          
          
            1
          
        
        ,
        .
        .
        .
        ,
        
          f
          
            i
          
          
            k
          
        
        .
      
    
    
  
  An FLM provides the probabilistic model 
  
    
      
        P
        f
        
          |
        
        
          f
          
            1
          
        
        ,
        .
        .
        .
        ,
        
          f
          
            N
          
        
      
    
    
  
 where the prediction of a factor 
  
    
      
        f
      
    
    
  
 is based on 
  
    
      
        N
      
    
    
  
 parents 
  
    
      
        
          f
          
            1
          
        
        ,
        .
        .
        .
        ,
        
          f
          
            N
          
        
      
    
    
  
.  For example, if 
  
    
      
        w
      
    
    
  
 represents a word token and 
  
    
      
        t
      
    
    
  
 represents a Part of speech tag for English, the expression 
  
    
      
        P
        
          w
          
            i
          
        
        
          |
        
        
          w
          
            i
            2
          
        
        ,
        
          w
          
            i
            1
          
        
        ,
        
          t
          
            i
            1
          
        
      
    
    
  
 gives a model for predicting current word token based on a traditional Ngram model as well as the Part of speech tag of the previous word.
A major advantage of factored language models is that they allow users to specify linguistic knowledge such as the relationship between word tokens and Part of speech in English, or morphological information (stems, root, etc.) in Arabic.
Like N-gram models, smoothing techniques are necessary in parameter estimation.  In particular, generalized back-off is used in training an FLM.

## Related

- [[Probabilistic context-free grammar]]
- [[Brown clustering]]
- [[Katz's back-off model]]
- [[Language model]]
- [[Latent Dirichlet allocation]]
- [[Markov information source]]
- [[N-gram]]
- [[Natural Language Toolkit]]
- [[Pachinko allocation]]
- [[Probabilistic latent semantic analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Factored_language_model