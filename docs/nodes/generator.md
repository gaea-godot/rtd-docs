---
weight: 30
---

# GaeaGenerator

The generator node need 3 resources to work: the `GaeaGraph` which contains the graph nodes and connections between them, the `GaeaGenerationSettings` which contains settings for the generator like the seed and the world size, and the `GaeaTaskPool` which contains the thread pool used to run the generator on a seperate thread.

![generator node](../assets/the-basics/generator-node.png)

## GaeaGraph

Usually the graph is saved in a separate resource but it can also be saved as a sub-resource of the generator. The graph is made up of nodes and connections. Each node has its own function, and the connections determine how data flows through the graph.

Adding the `GaeaGenerator` to your scene tree and selecting it will open the graph in the Gaea panel in the bottom of your editor.

The graph will already have a node: the output node. For now, this accepts one input: map data for layer 0. The **map data** type consists of a grid where each cell has its own `GaeaMaterial`, telling the `GaeaRenderer` nodes what to draw (we'll get to that in a minute).

The other data type you should know about is the **data grid**, a grid of numbers used in various different ways across the addon. From noise textures, to paths, and anything else. You can convert these to maps through various nodes, especially the **mapper** nodes. Check them out for a description!

Learn more about the graph in [Anatomy of a graph](../the-basics/anatomy-of-a-graph.md).