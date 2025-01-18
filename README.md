# TypeScript Type Error: string[] not assignable to string

This repository demonstrates a common TypeScript type error and its solution.  The error arises when attempting to pass an array of strings to a function expecting a single string argument. The `greeter` function expects a single string, but an array is provided.

## How to reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Compile and run the code using `tsc bug.ts && node bug.js`.

You will see a TypeScript compilation error.

## Solution

The solution involves modifying either the function signature or the way the array is handled to ensure type compatibility. See `bugSolution.ts` for the corrected code.