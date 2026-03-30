---
template: node.html
type: Sample
image: FalloffMap
category: Sampling > Generation
---

# Falloff Map

## Description

Generates a grid of values from `0.0` to `1.0` using the selected falloff shape.

Useful for generating an island-looking terrain when multiplied by the results of a :doc:`Noise <noise>` node.

## Falloff Shape

Options for falloff shapes include:
* Square
* Rounded Square
* Circle
* Squircle

## Start and End

The Start and End fields specify the start and end points of the falloff.

For example, a Start value of `0.0` and an End value of `1.0`, would result in an output that is white at the center that gradually reaches black at the edges.

On the other hand, a Start value of `0.5` with an End value also at `0.5` would result in an output that is fully white at the center that immediately reaches black halfway between the center and the edge.
