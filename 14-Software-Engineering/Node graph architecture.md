---
title: "Node graph architecture"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Node_graph_architecture"
wikipedia_categories: ["Software architecture"]
related: ["[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Agent architecture]]", "[[Anemic domain model]]", "[[Application domain]]", "[[Application server]]", "[[ArchiMate]]", "[[Architectural decision]]", "[[Architecturally significant requirements]]", "[[Architecture astronaut]]"]
---

# Node graph architecture

Node graph architecture is a software design structured around the notion of a node graph. Both the source code and the user interface are designed around the editing and composition (or linking) of atomic functional units. Node graphs are a type of visual programming language.
The source code for the software application is organized into atomic functional units called nodes. This is typically done using classes derived from a base class for all nodes. Each node can have inputs and outputs, which are typically also implemented using classes derived from base classes for all inputs and all outputs. Outputs and inputs can refer to each other, typically by holding pointers to instances of other outputs or inputs. When a node executes its functionality, it retrieves its inputs by following the pointers stored in its inputs to retrieve data output by other nodes. The node then executes its operation on these inputs to produce its own outputs. The ability to link nodes together in this way allows complex tasks or problems to be broken down into atomic nodal units that are easier to understand.
The user interface of the software application will often visually display the node graph to the user. Nodes are often drawn as rectangles, and connections between nodes are drawn with lines or splines.
The use of node graph architecture started in the 1960s. Today the use of node graphs has exploded. The fields of graphics, games, and machine learning are the main adopters of this software design with the majority of tools using node graph architecture.
To this day, there is some debate as to the benefits of visual programming and node graph architecture. Advocates highlight how the abstraction that node graphs provide makes the tool easier to use. Critics highlight how visual programming is too restrictive and how they must resort to modifying source code or scripts to accomplish their tasks.

## Related

- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Agent architecture]]
- [[Anemic domain model]]
- [[Application domain]]
- [[Application server]]
- [[ArchiMate]]
- [[Architectural decision]]
- [[Architecturally significant requirements]]
- [[Architecture astronaut]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Node_graph_architecture