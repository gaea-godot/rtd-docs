---
template: node.html
type: Sample
image: FloorWalker
category: Sampling > Generation
---

# Floor Walker

## Description

Generates a floor by using **walkers**, which move around and set cells where they walk to `1.0`, while changing direction and/or spawning new walkers.

This is how [Nuclear Throne](https://nuclearthrone.com) does its generation, for example, as seen [here](https://web.archive.org/web/20151009004931/https://www.vlambeer.com/2013/04/02/random-level-generation-in-wasteland-kings/).

## Algorithm

The algorithm starts from the `starting_point`. It spawns a `GaeaNodeWalker` with that position, and that walker starts moving randomly.

Depending on the chances configured, every 'turn' it has a chance to spawn a new walker, to change its direction, to be destroyed, to place cells in a bigger area, etc. 

All cells where it walks will be set to a value of `1.0`.

When a size of `max_cells` is reached, the generation will stop.