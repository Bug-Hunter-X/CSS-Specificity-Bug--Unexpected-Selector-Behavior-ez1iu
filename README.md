# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity.  In certain scenarios, the order of selector evaluation can unexpectedly affect which styles are applied, even when a more specific selector is present.

## Bug Description

The bug involves the interaction of ID selectors (`#`), class selectors (`.`), and type selectors (`div`).  Due to variations in CSS engine implementations, unexpected rendering can occur when selectors of similar specificity are evaluated in a specific order. 

The `bug.css` file contains the CSS code that reproduces the issue. The `bugSolution.css` demonstrates a solution.

## Solution

The solution provided in `bugSolution.css` shows using a more robust and less ambiguous way to structure your CSS selectors.