pay attention  to the cost. - Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 494).

Knuth's method of measuring an algorithms running time.
- use only the leading coefficient 
- only focus on the frequently repeated portion of the algorithm
- tilde notation

| description | function | factor for doubling hypothesis|
|---|---|---|
| constant | 1 | 1 |
| Row 2 Col 1 | Row 2 Col 2 | 1 |
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | 1 |
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
