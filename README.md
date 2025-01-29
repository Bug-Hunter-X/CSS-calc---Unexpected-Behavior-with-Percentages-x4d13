# CSS calc() Unexpected Behavior with Percentages

This repository demonstrates a common issue encountered when using the CSS `calc()` function with percentages and other units. The order of operations within `calc()` can lead to unexpected results and rendering issues, especially when nested or combined with other percentage calculations.

## Problem

The provided `bug.css` file shows how the standard `calc()` function behaves unexpectedly when a percentage is combined with a fixed unit, such as pixels.

## Solution

The `bugSolution.css` file offers a solution to address the issue by ensuring the units are consistent and order of operations are correctly managed.  In cases where complex nested calculations are involved, it may be necessary to break them down into smaller, more manageable parts.