# Julia Function Bug: Unexpected Negative Output

This repository demonstrates a common error in Julia functions involving incorrect handling of negative inputs.  The function `my_function` is intended to return the square of the input, regardless of sign. However, due to a simple error in the code, it returns negative values for negative inputs.

The `bug.jl` file contains the buggy code.  The solution, which corrects the behavior, is in `bugSolution.jl`.

This example highlights the importance of carefully considering the logic within conditional statements (if/elseif/else) and handling negative numbers appropriately in mathematical functions.