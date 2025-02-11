# CSS `calc()` Bug: Unexpected Behavior with Percentages and Other Units

This repository demonstrates a potential bug or unexpected behavior related to the use of the `calc()` function in CSS, specifically when combining percentage values with other units (e.g., pixels). In certain situations, the results of the calculations performed by `calc()` may not match expectations due to how browsers handle unit conversions and the order of operations.

The `bug.css` file contains CSS code that illustrates the problem. The `bugSolution.css` demonstrates a potential approach to avoid or mitigate the issue.

**How to reproduce:**
1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the rendered layout; the results might deviate from what is expected based on the calculated width.

**Potential Solution:** Carefully review your `calc()` expressions to understand the potential order of operations. Consider using units consistently or breaking down complex calculations into simpler steps to improve predictability.