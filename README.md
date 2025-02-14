# Invalid Expression in CSS calc() Function

This repository demonstrates a common error involving the CSS `calc()` function.  The error occurs when providing an invalid expression within the `calc()` function, leading to unexpected results or the entire calculation being ignored.

The `bug.css` file shows the incorrect implementation, while `bugSolution.css` presents the corrected version.

## Bug:
The `calc()` function in `bug.css` attempts to calculate a width using an invalid expression, resulting in the calculation failing and potentially applying a default width.

## Solution:
The corrected version in `bugSolution.css` ensures a valid expression inside `calc()`, accurately calculating the desired width.