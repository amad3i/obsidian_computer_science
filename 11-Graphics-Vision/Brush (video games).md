---
title: "Brush (video games)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Brush_(video_games)"
wikipedia_categories: ["Video game development"]
related: ["[[2.5D]]", "[[2022–2026 video game industry layoffs]]", "[[AAA (video game industry)]]", "[[AbleGamers]]", "[[Academy of Interactive Arts & Sciences]]", "[[Amazon Lumberyard]]", "[[Artificial intelligence in video games]]", "[[Asset flip]]", "[[Atari 2600 homebrew]]", "[[Australian Game Developers Conference]]"]
---

# Brush (video games)

Brushes are templates used in some 3D video game engines, such as the Quake engine, its derivatives the GoldSrc and Source game engines, or the Unreal Engine, to construct levels. Brushes can be primitive shapes (such as cubes, spheres and cones), pre-defined shapes (such as staircases), or custom shapes (such as prisms and other polyhedra).
In order to describe these shapes mathematically, each brush is made up of planes that define its boundaries. A plane can be represented by an equation in 3D space, which looks like this:

  
    
      
        a
        x
        b
        y
        c
        z
        d
        0
      
    
    
  

This equation describes a single flat surface (or plane) in 3D space, where a, b, and c are coefficients that determine the orientation of the plane, and d is a constant that shifts the plane along its axis.
To construct a brush, the game engine uses multiple planes working together. For example, a cube can be defined by six planes, each restricting space within a certain region. Here’s how a set of three planes would be represented mathematically:

  
    
      
        
          
            
              
                
                  
                    a
                    
                      1
                    
                  
                  x
                  
                    b
                    
                      1
                    
                  
                  y
                  
                    c
                    
                      1
                    
                  
                  z
                  
                    d
                    
                      1
                    
                  
                  0
                
              
              
                
                  
                    a
                    
                      2
                    
                  
                  x
                  
                    b
                    
                      2
                    
                  
                  y
                  
                    c
                    
                      2
                    
                  
                  z
                  
                    d
                    
                      2
                    
                  
                  0
                
              
              
                
                  
                    a
                    
                      3
                    
                  
                  x
                  
                    b
                    
                      3
                    
                  
                  y
                  
                    c
                    
                      3
                    
                  
                  z
                  
                    d
                    
                      3
                    
                  
                  0
                
              
            
            
          
        
      
    
    
  

Each of these equations corresponds to a different plane that helps define the shape of the brush.
In some engines, such as Unreal, brushes are categorized as either additive or subtractive. Additive brushes add volume to the level, forming walls, platforms, or other structures, while subtractive brushes carve out spaces within these volumes, like windows or doorways.
During the map compilation process, brushes are turned into meshes that can be rendered by the game engine. Often brushes are restricted to convex shapes only, as this reduces the complexity of the binary space partitioning process. However, using CSG operations, complex rooms and objects can be created by adding, subtracting and intersecting brushes to and from one another. Additionally, brushes can be used as liquids or as an area trigger.

## Related

- [[2.5D]]
- [[2022–2026 video game industry layoffs]]
- [[AAA (video game industry)]]
- [[AbleGamers]]
- [[Academy of Interactive Arts & Sciences]]
- [[Amazon Lumberyard]]
- [[Artificial intelligence in video games]]
- [[Asset flip]]
- [[Atari 2600 homebrew]]
- [[Australian Game Developers Conference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Brush_(video_games)