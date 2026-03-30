---
template: node.html
type: Sample
image: FloorWalker
category: Sampling > Generation
---

# FloorWalker

## Description

Generates a floor by using [b]walkers[/b], which move around and set cells where they walk to `1.0`, while changing direction and/or spawning new walkers.

## Enums

### Enum #1

There is currently no description for the enum #1.

- XY Axis
- XZ Axis

## Arguments
| Type                                                       | Name (Display Name)                                 | Description                                                                   | Default           |
|------------------------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------------------|-------------------|
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `max_cells` (Max Cells)                             | There is currently no description for the argument `max_cells`.               | 100               |
| [Vector3i](../the-basics/anatomy-of-a-graph.md#slot-types) | `starting_position` (Starting Position)             | There is currently no description for the argument `starting_position`.       | Vector3i(0, 0, 0) |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `direction_change_chance` (Direction Change Chance) | There is currently no description for the argument `direction_change_chance`. | 50                |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `rotate_90_weight` (Rotate 90 Weight)               | There is currently no description for the argument `rotate_90_weight`.        | 40                |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `rotate_-90_weight` (Rotate 90 Weight)              | There is currently no description for the argument `rotate_-90_weight`.       | 40                |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `rotate_180_weight` (Rotate 180 Weight)             | There is currently no description for the argument `rotate_180_weight`.       | 40                |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `new_walker_chance` (New Walker Chance)             | There is currently no description for the argument `new_walker_chance`.       | 5                 |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `destroy_walker_chance` (Destroy Walker Chance)     | There is currently no description for the argument `destroy_walker_chance`.   | 5                 |
| [int](../the-basics/anatomy-of-a-graph.md#slot-types)      | `bigger_room_chance` (Bigger Room Chance)           | There is currently no description for the argument `bigger_room_chance`.      | 15                |
| [Range](../the-basics/anatomy-of-a-graph.md#slot-types)    | `bigger_room_size_range` (Bigger Room Size Range)   | There is currently no description for the argument `bigger_room_size_range`.  | 2-3               |

## Outputs

### [Sample](../the-basics/anatomy-of-a-graph.md#slot-types) - `result` (Result)

There is currently no description for output `result`.