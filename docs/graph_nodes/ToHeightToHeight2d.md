---
template: graph_node.html
type: Sample
image: ToHeightToHeight2d
category: Sampling > Transformation
---

# ToHeight2D

## Description

Transforms [reference](#arguments) into a new sample grid where the height of each column is determined by [height_offset](#arguments) + ([reference](#arguments) * [displacement_intensity](#arguments)).

References all the x values of the [reference_y](#arguments) row.

## Enums

### Enum #1

There is currently no description for the enum #1.

- 2D
- 3D

## Arguments
| Type                                                     | Name (Display Name)                               | Description                                                                  | Default |
|----------------------------------------------------------|---------------------------------------------------|------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `reference` (Reference)                           | There is currently no description for the argument `reference`.              |         |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)    | `reference_y` (Reference Y)                       | There is currently no description for the argument `reference_y`.            | 0       |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)    | `height_offset` (Height Offset)                   | There is currently no description for the argument `height_offset`.          | 0       |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)    | `displacement_intensity` (Displacement Intensity) | There is currently no description for the argument `displacement_intensity`. | 16      |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `gradient_intensity` (Gradient Intensity)         | There is currently no description for the argument `gradient_intensity`.     | 1.0     |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (Result)

There is currently no description for output `result`.