# CSS `calc()` Function Errors

This repository demonstrates common errors encountered when using the CSS `calc()` function.  Specifically, it highlights issues related to missing units and incorrect operator precedence.

The `bug.css` file contains examples of problematic `calc()` usage.  The `bugSolution.css` file provides corrected versions.

## Common Mistakes

* **Missing Units:** Ensure all values within the `calc()` function have units (e.g., `px`, `%`, `em`).  Missing units often lead to unexpected behavior or errors.
* **Operator Precedence:** Carefully consider the order of operations within the calculation. Parentheses are crucial for controlling precedence.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` (or similar) in a web browser.
3. Observe the unexpected layout due to incorrect `calc()` usage.
4. Compare with `bugSolution.html` (or similar) which shows the corrected layout.

## Solution

Always include units with all values in `calc()` and use parentheses liberally to specify the order of calculations to avoid unexpected results. 