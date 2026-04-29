---
template: graph_node.html
type: Sample
image: RandomFilter
category: Sampling > Filters
---

# RandomFilter

## Description

Filters [sample](#arguments) to only the cells that pass the [chance](#arguments) check.

## Arguments
| Type                                                     | Name (Display Name)   | Description                                                     | Default |
|----------------------------------------------------------|-----------------------|-----------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `input_grid` (Sample) | Sample to be filtered.                                          |         |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)    | `chance` (Chance)     | For each cell, the chance (in percentage) it's filtered or not. | 50      |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `filtered_grid` (Filtered Sample)

Returns the Sample after filtering has been applied.