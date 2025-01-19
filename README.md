# CSS `calc()` Bug: Incorrect Handling of Negative Values

This repository demonstrates a lesser-known bug in some browsers' handling of negative values produced by the CSS `calc()` function. When `calc()` results in a negative value, particularly when mixing percentages and absolute units, the rendering may be unexpected.

The `bug.css` file shows the problematic code. The `bugSolution.css` provides a workaround.