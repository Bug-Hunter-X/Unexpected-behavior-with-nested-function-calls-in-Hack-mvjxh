# Unexpected Behavior with Nested Function Calls in Hack

This repository demonstrates an unexpected behavior encountered when using nested function calls in Hack. The program consists of three functions: `foo`, `bar`, and `baz`, where each function calls the preceding function. The `main` function calls `baz` with the argument 5, and the expected output is 11 (5 + 1 + 2 + 3).

However, the actual output differs from the expected output. This issue is likely related to how Hack handles function calls or integer arithmetic within nested function structures.

The bug.hack file contains the original code exhibiting the unexpected behavior. The bugSolution.hack file provides a corrected version of the code, demonstrating how to resolve the issue and achieve the expected output.