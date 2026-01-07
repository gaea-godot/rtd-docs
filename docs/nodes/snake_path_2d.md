---
template: node.html
type: Sample
image: SnakePath2d
category: Sampling > Generation
---

# Snake Path

## Description

Generates a path that goes from the top of the world to the bottom, flagging the exits from each cell (up, down, left, right).

## Algorithm

The algorithm starts from a random point in the top row of the generation area. 

From there, it'll either move left, right or down, depending on the configured weights.

If it reaches a border, and tries to move outside the bounds of the generation area, it'll drop down.

The algorithm finishes when it attempts to move down despite already reaching the bottom row of cells.

## Weights

Each movement direction (left, right, down) has a weight value.

Take these weights as an example:
- Left: 40
- Right: 50
- Down: 10

For the weight above, the algorithm can be expected to move left 40% of the time, right 50% of the time, and down 10% of the time.

Weights do not have to sum to 100.

## Flags

Each cell has a value with flags representing the path the algorithm took. For example whenever it drops down, the cell where it ended up will have the `up` flag, showing that the path is connected with an exit to the cell above (which has the `down` flag).

This is how [Spelunky](https://www.spelunkyworld.com/) generates its level layouts, as seen [here](https://tinysubversions.com/spelunkyGen/).