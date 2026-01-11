---
template: node.html
type: Sample
image: DistanceFilter
category: Sampling > Filters
---

# DistanceFilter

## Description

Filters [param sample] to only the cells at a distance from [param to_point] in [param distance_range].

## Arguments
| Type    | Name             | Description                                                               | Default               |
|---------|------------------|---------------------------------------------------------------------------|-----------------------|
| Sample  | `Sample`         | Sample to be filtered.                                                    |                       |
| Vector3 | `To Point`       | Reference point for distance calculations.                                | Vector3(0, 0, 0)      |
| Range   | `Distance Range` | For each cell, if it's outside this range of distance, it's filtered out. | {"max":1.0,"min":0.0} |

## Outputs

### Filtered Sample [Sample]

Returns the Sample after filtering has been applied.