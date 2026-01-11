---
template: node.html
type: Sample
image: ThresholdFilter
category: Sampling > Filters
---

# ThresholdFilter

## Description

Filters [param sample] to only the cells of a value in [param range].

## Arguments
| Type   | Name     | Description                                                   | Default               |
|--------|----------|---------------------------------------------------------------|-----------------------|
| Sample | `Sample` | Sample to be filtered.                                        |                       |
| Range  | `Range`  | For each cell, if it's outside this range, it's filtered out. | {"max":1.0,"min":0.0} |

## Outputs

### Filtered Sample [Sample]

Returns the Sample after filtering has been applied.