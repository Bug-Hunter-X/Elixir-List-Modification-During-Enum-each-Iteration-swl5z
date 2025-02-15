# Elixir List Modification During Enum.each Iteration

This repository demonstrates a common error in Elixir when attempting to modify a list while iterating over it using `Enum.each`. The issue arises because the list modification within the anonymous function doesn't affect the list in the outer scope.

The `bug.exs` file contains the erroneous code, highlighting the problem. The `bugSolution.exs` demonstrates a corrected approach using `Enum.filter` or `for` comprehension.