---
template: graph_node.html
type: Sample
image: SampleOpRemap
category: Sampling > Operations > Scalar
---

# Remap (remap(A, ...))

## Description

Maps [a](#arguments) from range `[istart, istop]` to `[ostart, ostop]`.

Operates over all cells of [A](#arguments), [a](#arguments) being the cells' value.

## Enums

### Enum #1

There is currently no description for the enum #1.

- Add
- Subtract
- Multiply
- Divide
- Power
- Max
- Min
- Abs
- Ceil
- Floor
- Round
- Clamp
- Remap
- Sign
- Smoothstep
- Step
- Wrap

## Arguments
| Type                                                     | Name (Display Name)     | Description                                                     | Default |
|----------------------------------------------------------|-------------------------|-----------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `a` (A)                 | There is currently no description for the argument `a`.         |         |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `in_start` (in_start)   | There is currently no description for the argument `in_start`.  | 0.0     |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `in_stop` (in_stop)     | There is currently no description for the argument `in_stop`.   | 0.0     |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `out_start` (out_start) | There is currently no description for the argument `out_start`. | 0.0     |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `out_stop` (out_stop)   | There is currently no description for the argument `out_stop`.  | 0.0     |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (remap(A, ...))

There is currently no description for output `result`.