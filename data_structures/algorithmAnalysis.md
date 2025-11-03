pay attention  to the cost. - Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 494).

Knuth's method of measuring an algorithms running time.
- use only the leading coefficient 
- only focus on the frequently repeated portion of the algorithm
- tilde notation

| Description | Function | Factor for doubling hypothesis|
|---|---|---|
| constant | 1 | 1 |
| logarithmic | log n | 1 |
| linear | n | 2 |
| linearithmic | n log(n) | 2 |
| quadratic | n^2 | 4 |
| cubic | n^3 | 8 |
| exponential | 2^n | 2^n |


| Type| Bytes |
|---|---|
| boolean | 1 |
| byte | 1 |
| char | 2 |
| int | 4 |
| float | 4 |
| long | 8 |
| double | 8 |

### Determining the memory usage of objects
(typically rounded to multiples of 8)
Overhead - 16 bytes
Instance variables - 8 bytes(each)
Additional data like arrays, booleans, and any contents of the algorithm.

