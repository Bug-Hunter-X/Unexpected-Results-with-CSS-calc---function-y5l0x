# Unexpected Results with CSS calc() function

This repository demonstrates a common yet often overlooked issue when using the CSS `calc()` function: unexpected behavior resulting from incorrect nesting or inconsistent unit usage.

The `bug.css` file showcases a problematic example, while `bugSolution.css` provides the corrected implementation.

## Bug Description:
The `calc()` function in CSS, while powerful, can produce errors if not used carefully.  Improperly nesting expressions or mixing units (e.g., pixels and percentages) can cause unexpected results. Forgetting spaces around the operators is also a frequent mistake. 

## Solution:
The corrected version ensures proper spacing around operators and consistent unit usage throughout the calculation. Nesting is simplified, and clarity is improved to prevent misinterpretations by the browser.