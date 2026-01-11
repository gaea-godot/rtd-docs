---
template: node.html
type: Sample
image: FlagsFilter
category: Sampling > Filters
---

# FlagsFilter

## Description

Filters [param sample] to only the cells that match the flag conditions.

## Arguments
| Type   | Name            | Description                                                                                                                   | Default |
|--------|-----------------|-------------------------------------------------------------------------------------------------------------------------------|---------|
| Sample | `Sample`        | Sample to be filtered.                                                                                                        |         |
| bool   | `Match All`     | Whether or not to require matching all flags in [param match_flags], or only one.                                             | false   |
| Flags  | `Match Flags`   | For each cell, if it has any or all of these flags (depending on [param match_all]), it's kept in. If not, it's filtered out. | []      |
| Flags  | `Exclude Flags` | For each cell, if it has any of these flags, it's always filtered out.                                                        | []      |

## Outputs

### Filtered Sample [Sample]

Returns the Sample after filtering has been applied.