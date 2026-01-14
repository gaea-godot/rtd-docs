---
template: node.html
type: Sample
image: SnakePath2d
category: Sampling > Generation
---

# SnakePath2D

## Description

Generates a path that goes from the top of the world to the bottom, with each cell consisting of flags that indicate their exits (up, down, left, right).

## Arguments
| Type                                                               | Name (Display Name)                     | Description                                                             | Default |
|--------------------------------------------------------------------|-----------------------------------------|-------------------------------------------------------------------------|---------|
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)              | `move_left_weight` (Move Left Weight)   | There is currently no description for the argument `move_left_weight`.  | 40      |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)              | `move_right_weight` (Move Right Weight) | There is currently no description for the argument `move_right_weight`. | 40      |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)              | `move_down_weight` (Move Down Weight)   | There is currently no description for the argument `move_down_weight`.  | 40      |
| [BitmaskExclusive](../the-basics/anatomy-of-a-graph.md#slot-types) | `left` (Left)                           | There is currently no description for the argument `left`.              | 1       |
| [BitmaskExclusive](../the-basics/anatomy-of-a-graph.md#slot-types) | `right` (Right)                         | There is currently no description for the argument `right`.             | 2       |
| [BitmaskExclusive](../the-basics/anatomy-of-a-graph.md#slot-types) | `down` (Down)                           | There is currently no description for the argument `down`.              | 4       |
| [BitmaskExclusive](../the-basics/anatomy-of-a-graph.md#slot-types) | `up` (Up)                               | There is currently no description for the argument `up`.                | 8       |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (Result)

There is currently no description for output `result`.