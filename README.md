# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity and the `!important` declaration.  The bug showcases a situation where a more specific selector is overridden by a less specific selector due to the use of `!important`.

The `bug.css` file contains the erroneous CSS code, while `bugSolution.css` provides a corrected version. The README explains the root cause and offers a solution.

## Bug Description

The unexpected behavior stems from the conflict between CSS specificity and the `!important` flag.  Even though a more specific selector is present, the `!important` declaration in the less specific selector wins, leading to incorrect styling.

## Solution

The solution avoids using `!important` unless absolutely necessary.  By carefully structuring CSS rules and adhering to best practices, this type of conflict can be easily avoided.