# Unexpected Behavior with Loose Equality in JavaScript

This example demonstrates a common pitfall in JavaScript: the use of loose equality (`==`) to compare values. Loose equality does not perform type checking and can lead to unexpected results when comparing values of different types.

The `foo` function aims to check the sign of a number, treating null as 0. However, due to the loose equality check (`x == null`), it incorrectly returns 1 for the input 0.