---
template: node.html
type: Sample
image: SampleOpStep
category: Sampling > Operations > Scalar
---

# Step (step(A, edge))

## Description

Returns `0` if [a](#arguments) < [edge](#arguments), otherwise `1`.

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
| Type                                                     | Name (Display Name) | Description                                                | Default |
|----------------------------------------------------------|---------------|------------------------------------------------------------|---------|
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `a` (A)       | There is currently no description for the argument `a`.    |         |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `edge` (edge) | There is currently no description for the argument `edge`. | 0.0     |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (step(A, edge))

There is currently no description for output `result`.