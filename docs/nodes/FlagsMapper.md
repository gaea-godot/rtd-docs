---
template: node.html
type: Map
image: FlagsMapper
category: Map > Mappers
---

# FlagsMapper

## Description

Maps every cell of [reference](#arguments) that matches the flag conditions to [material](#arguments).

A cell being mapped to [material](#arguments) means that, in the output Map, that cell will contain that material.

## Arguments
| Type                                                       | Name (Display Name)             | Description                                                                                                                             | Default |
|------------------------------------------------------------|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types)   | `reference` (Reference)         | A grid of type Sample, which will be used as a reference for mapping.                                                                   |         |
| [Material](../the-basics/anatomy-of-a-graph.md#slot-types) | `material` (Material)           | The GaeaMaterial used for the mapping.                                                                                                  | null    |
| [bool](../the-basics/anatomy-of-a-graph.md#slot-types)     | `match_all` (Match All)         | Whether or not to require matching all flags in [match_flags](#arguments), or only one.                                                 | false   |
| [Flags](../the-basics/anatomy-of-a-graph.md#slot-types)    | `match_flags` (Match Flags)     | For each cell, if it has any or all of these flags (depending on [match_all](#arguments)), it will be mapped to [material](#arguments). | []      |
| [Flags](../the-basics/anatomy-of-a-graph.md#slot-types)    | `exclude_flags` (Exclude Flags) | For each cell, if it has any of these flags, it will always be empty.                                                                   | []      |

## Outputs

### [Map](../the-basics/anatomy-of-a-graph.md#slot-types) - `map` (Map)

The final, generated map.