---
template: graph_node.html
type: Sample
image: DistanceFilter
category: Sampling > Filters
---

# DistanceFilter

## Description

Filters [sample](#arguments) to only the cells at a distance from [to_point](#arguments) in [distance_range](#arguments).

## Arguments
| Type                                                      | Name (Display Name)               | Description                                                               | Default          |
|-----------------------------------------------------------|-----------------------------------|---------------------------------------------------------------------------|------------------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types)  | `input_grid` (Sample)             | Sample to be filtered.                                                    |                  |
| [Vector3](../the-basics/anatomy-of-a-graph.md#slot-types) | `to_point` (To Point)             | Reference point for distance calculations.                                | Vector3(0, 0, 0) |
| [Range](../the-basics/anatomy-of-a-graph.md#slot-types)   | `distance_range` (Distance Range) | For each cell, if it's outside this range of distance, it's filtered out. | 0.0-1.0          |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `filtered_grid` (Filtered Sample)

Returns the Sample after filtering has been applied.