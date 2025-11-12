## Hilberts 3 Mathematic statements
- Math is consistent
- Math is complete
- Math is decidable

## Liars paradox
Hypothesis, every statement can be categorized as true or false. 
"This statement is false" fits neither thus proving that there can be inconsistency in math

## The halting problem(1937)
It is impossible to solve the halting problem because knowing whether a program will enter into an infinite loop is impossible to define. In the textbook it says its like a compiler checking if itself will be in an infinite loop while compiling, it could enter an infinite loop in the input which would halt the original one but if the input does halt then the orignal compiler does not halt. 

### Problem Reduction
A problem A reduces to another problem B if, given  a subroutine for B, we can solve any instance a of A as follows:
- Process a and create instances b1, b2, … of B.
- Using the subroutine for B, obtain solutions to b1, b2, ….
- Use the solutions of b1, b2, … to help solve a. 
Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 811).

## Rice's Theorem(1951)
Determining whether a given program has any given  functional property is unsolvable. 
