# CSS Specificity Conflict Bug

This repository demonstrates a common issue in CSS: specificity conflicts.  A more specific selector can override a less specific one, even if it seems counter-intuitive.

The `bug.css` file contains the CSS code with the conflict. The `bugSolution.css` file offers a solution.

To reproduce the issue, open `bug.html` in your web browser. The element will be blue, not green as intended.

The solution modifies the order or specificity of the selectors to achieve the desired outcome.