---
template: graph_node.html
type: Sample
image: Noise2d
category: Sampling > Noise
---

# Noise2D

## Description

Creates a grid of values from `0` to `1` based on a noise algorithm.
[b]Ignores the z axis.[/b]

## Enums

### Enum #1

There is currently no description for the enum #1.

- Simplex
- Simplex Smooth
- Cellular
- Perlin
- Value Cubic
- Value

## Arguments
| Type                                                    | Name (Display Name)       | Description                                                      | Default |
|---------------------------------------------------------|---------------------------|------------------------------------------------------------------|---------|
| [float](../the-basics/anatomy-of-a-graph.md#slot-types) | `frequency` (Frequency)   | There is currently no description for the argument `frequency`.  | 0.01    |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types) | `lacunarity` (Lacunarity) | There is currently no description for the argument `lacunarity`. | 2.0     |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)   | `octaves` (Octaves)       | There is currently no description for the argument `octaves`.    | 5       |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `noise` (Noise)

There is currently no description for output `noise`.