---
template: node.html
type: Sample
image: ThresholdFilter
category: Sampling > Filters
---

# ThresholdFilter

## Description

Filters [sample](#arguments) to only the cells with a value in [range](#arguments).

## Arguments
| Type                                                     | Name (Display Name)   | Description                                                                                               | Default |
|----------------------------------------------------------|-----------------------|-----------------------------------------------------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `input_grid` (Sample) | Sample to be filtered.                                                                                    |         |
| [Range](../the-basics/anatomy-of-a-graph.md#slot-types)  | `range` (Range)       | For each cell, if its value is inside (inclusive) this range, it's kept in. Otherwise, it's filtered out. | 0.0-1.0 |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `filtered_grid` (Filtered Sample)

Returns the Sample after filtering has been applied.