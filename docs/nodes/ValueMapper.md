---
template: node.html
type: Map
image: ValueMapper
category: Map > Mappers
---

# ValueMapper

## Description

Maps every cell of [reference](#arguments) equal to [value](#arguments) to [material](#arguments).

A cell being mapped to [material](#arguments) means that, in the output Map, that cell will contain that material.

## Arguments
| Type                                                       | Name (Display Name)     | Description                                                                                                             | Default |
|------------------------------------------------------------|-------------------------|-------------------------------------------------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types)   | `reference` (Reference) | A grid of type Sample, which will be used as a reference for mapping.                                                   |         |
| [Material](../the-basics/anatomy-of-a-graph.md#slot-types) | `material` (Material)   | The GaeaMaterial used for the mapping.                                                                                  | null    |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)    | `value` (Value)         | For each cell, if its value is equal to this, it will be mapped to [material](#arguments). Otherwise, it will be empty. | 0.0     |

## Outputs

### [Map](../the-basics/anatomy-of-a-graph.md#slot-types) - `map` (Map)

The final, generated map.