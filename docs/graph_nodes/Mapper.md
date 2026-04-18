---
template: graph_node.html
type: Map
image: Mapper
category: Map > Mappers
---

# Mapper

## Description

Maps all non-empty cells in [reference](#arguments) to [material](#arguments).

A cell being mapped to [material](#arguments) means that, in the output Map, that cell will contain that material.

## Arguments
| Type                                                       | Name (Display Name)     | Description                                                           | Default |
|------------------------------------------------------------|-------------------------|-----------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types)   | `reference` (Reference) | A grid of type Sample, which will be used as a reference for mapping. |         |
| [Material](../the-basics/anatomy-of-a-graph.md#slot-types) | `material` (Material)   | The GaeaMaterial used for the mapping.                                | null    |

## Outputs

### [Map](../the-basics/anatomy-of-a-graph.md#slot-types) - `map` (Map)

The final, generated map.