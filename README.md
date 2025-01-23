# Type Error in TypeScript function
This repository contains a simple TypeScript program that demonstrates a common type error. The program defines a function that expects a string argument, but it is called with an array of strings. This results in a type error.

The solution to this error is to either modify the function to accept an array of strings or to pass a single string to the function.  The solution file shows both methods.

## How to run
1. Clone this repository.
2. Navigate to the repository directory.
3. Run the command `tsc bug.ts` to compile the code.
4. Run the command `node bug.js` to execute the compiled code.
5. Observe the error.
6. Repeat steps 3 and 4 for `bugSolution.ts` and `bugSolution.js` to see the solution.