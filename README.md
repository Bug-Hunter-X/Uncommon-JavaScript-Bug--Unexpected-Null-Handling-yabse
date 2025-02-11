# Uncommon JavaScript Bug: Unexpected Null Handling

This repository demonstrates a subtle bug in JavaScript related to null value handling.  The `foo` function attempts to handle null values by returning 0 if either input is null. However, this might not be the appropriate behavior in all scenarios.  The bug is in the unintended behavior when null values are passed.

The solution demonstrates a more robust approach to handling nulls, offering greater flexibility and control.

## Bug
The primary issue lies in the simplistic null check.  In some cases, returning 0 when a null value is present might mask deeper problems or lead to unexpected results.