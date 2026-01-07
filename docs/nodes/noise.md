---
template: node.html
image: Noise2d
type: Sample
category: Sampling > Noise
---

# Noise 2D and 3D

## Description

Samples a grid of values from `0.0` to `1.0` using the selected noise algorithm.

## Algorithms

Utilizes [FastNoiseLite](https://docs.godotengine.org/en/stable/classes/class_fastnoiselite.html) under the hood, and as a result it supports all of it's noise types.

Noise 2D uses [FastNoiseLite](https://docs.godotengine.org/en/stable/classes/class_fastnoiselite.html)'s `get_noise_2d` method, whereas Noise 3D uses the `get_noise_3d` method.

