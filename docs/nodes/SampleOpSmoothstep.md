---
template: node.html
type: Sample
image: SampleOpSmoothstep
category: Sampling > Operations > Scalar
---

# Smoothstep (smoothstep(from, to, A))

## Description

Returns `0` if [a](#arguments) < [from](#arguments), `1` if [a](#arguments) > [to](#arguments), otherwise returns an interpolated value between `0` and `1`.

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
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `from` (from) | There is currently no description for the argument `from`. | 0.0     |
| [float](../the-basics/anatomy-of-a-graph.md#slot-types)  | `to` (to)     | There is currently no description for the argument `to`.   | 0.0     |
| [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) | `a` (A)       | There is currently no description for the argument `a`.    |         |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (smoothstep(from, to, A))

There is currently no description for output `result`.