# CSS Calc() Unexpected Behavior with Percentages and Viewport Units

This repository demonstrates an uncommon issue in CSS involving the `calc()` function when combining percentages and viewport units (like `vw` or `vh`). The calculated value may not be what you intuitively expect.

The `bug.css` file contains the problematic code.  The `bugSolution.css` file shows the solution.

The issue arises from how `calc()` handles the order of operations and the context of percentages.  In some cases, the percentage is calculated relative to a different element or value than intended, leading to unexpected results.