---
template: node.html
type: Sample
image: RandomFilter
category: Sampling > Filters
---

# RandomFilter

## Description

Filters [param sample] to only the cells that pass the [param chance] check.

## Arguments
| Type   | Name     | Description                                                     | Default |
|--------|----------|-----------------------------------------------------------------|---------|
| Sample | `Sample` | Sample to be filtered.                                          |         |
| int    | `Chance` | For each cell, the chance (in percentage) it's filtered or not. | 50      |

## Outputs

### Filtered Sample [Sample]

Returns the Sample after filtering has been applied.