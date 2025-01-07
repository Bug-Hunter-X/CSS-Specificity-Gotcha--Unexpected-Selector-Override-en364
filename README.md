# CSS Specificity Gotcha: Unexpected Selector Override

This repository demonstrates a subtle CSS specificity issue that can be difficult to debug.  The problem involves the interaction between ID selectors, class selectors, and element selectors, leading to unexpected cascading behavior.

## Bug Description

The provided `bug.css` file contains CSS rules that appear to be straightforward. The goal is to style a paragraph element within a div with the id 'box'.  However, due to CSS specificity rules, the expected styling does not apply.

## Solution

The `bugSolution.css` file provides the correct styling, demonstrating how to resolve this issue.  Understanding CSS specificity is key to avoiding and solving similar issues.  The solution demonstrates different ways to achieve the desired outcome.