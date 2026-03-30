---
template: node.html
type: Map
image: ThresholdMapper
category: Map > Mappers
---

# ThresholdMapper

## Description

Maps every cell of [reference](#arguments) with a value in [range](#arguments) to [material](#arguments).

A cell being mapped to [material](#arguments) means that, in the output Map, that cell will contain that material.

## Arguments
| Type                                                       | Name (Display Name)     | Description                                                                                                                 | Default |
|------------------------------------------------------------|-------------------------|-----------------------------------------------------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types)   | `reference` (Reference) | A grid of type Sample, which will be used as a reference for mapping.                                                       |         |
| [Material](../the-basics/anatomy-of-a-graph.md#slot-types) | `material` (Material)   | The GaeaMaterial used for the mapping.                                                                                      | null    |
| [Range](../the-basics/anatomy-of-a-graph.md#slot-types)    | `range` (Range)         | For each cell, if its value is inside this range, it will be mapped to [material](#arguments). Otherwise, it will be empty. | 0.0-1.0 |

## Outputs

### [Map](../the-basics/anatomy-of-a-graph.md#slot-types) - `map` (Map)

The final, generated map.