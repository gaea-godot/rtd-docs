---
template: graph_node.html
type: Sample
image: SampleOpClamp
category: Sampling > Operations > Scalar
---

# Clamp (clamp(A, min, max))

## Description

Constrains [a](#arguments) to lie between [min](#arguments) and [max](#arguments) (inclusive).

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
| Type                                                     | Name (Display Name) | Description                                               | Default |
|----------------------------------------------------------|-------------|-----------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `a` (A)     | There is currently no description for the argument `a`.   |         |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `min` (min) | There is currently no description for the argument `min`. | 0.0     |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `max` (max) | There is currently no description for the argument `max`. | 0.0     |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (clamp(A, min, max))

There is currently no description for output `result`.