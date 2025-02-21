# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The bug showcases how unexpected inheritance behavior can occur when dealing with nested elements and selectors with varying specificity.

## Bug Description
The provided CSS code exhibits unexpected behavior concerning color inheritance and font sizes applied to nested elements within a container. The specificity of selectors plays a crucial role, leading to unexpected results that may be difficult to debug for developers unfamiliar with these nuances of CSS.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to see the problematic CSS code.
3. Create an HTML file to test the CSS (example provided in `index.html`).
4. Observe the unexpected color and font-size rendering in your browser.

## Solution
The solution file, `bugSolution.css`, provides a corrected version of the CSS that addresses the specificity and inheritance issues.  This showcases how to improve the selectors to achieve the desired styling.