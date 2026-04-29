---
template: graph_node.html
type: Sample
image: FlagsFilter
category: Sampling > Filters
---

# FlagsFilter

## Description

Filters [sample](#arguments) to only the cells that match the flag conditions.

## Arguments
| Type                                                     | Name (Display Name)             | Description                                                                                                                         | Default |
|----------------------------------------------------------|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `input_grid` (Sample)           | Sample to be filtered.                                                                                                              |         |
| [bool](../the-basics/anatomy-of-a-graph.md#slot-types)   | `match_all` (Match All)         | Whether or not to require matching all flags in [match_flags](#arguments), or only one.                                             | false   |
| [Flags](../the-basics/anatomy-of-a-graph.md#slot-types)  | `match_flags` (Match Flags)     | For each cell, if it has any or all of these flags (depending on [match_all](#arguments)), it's kept in. If not, it's filtered out. | []      |
| [Flags](../the-basics/anatomy-of-a-graph.md#slot-types)  | `exclude_flags` (Exclude Flags) | For each cell, if it has any of these flags, it's always filtered out.                                                              | []      |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `filtered_grid` (Filtered Sample)

Returns the Sample after filtering has been applied.