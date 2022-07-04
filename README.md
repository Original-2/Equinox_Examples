# Equinox_Examples

These examples are all reimplementations of the [keras examples](https://keras.io/examples/) unless otherwise stated and I am implementing them with [equinox](https://github.com/patrick-kidger/equinox), a Jax library which is used to represent parameterised functions as pytrees.

## Why use equinox / jax-based libraries

Tensorflow is bloated. This means it is a very large package with lots of useless redundancy and legacy features; tensorflow is therefore hard to understand. Tensorflow is also (often) very slow. I cannot say the same about pytorch as I have little experience with it. However, equinox is fast, lightweight and easy to use.
