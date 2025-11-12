## Turing Machine Model
- A finite number of states, each of wich is a left, right, or halt state
- A set of transitions that specify which state is next and which symbol to write
- A tape that holds strings of symbols 
- A tape heap capable of reading or writing a symbol and traversing the tape to read/write the next symbol

Compact Trace format -  a compact illustration of the TM 

State-Table representation - a table to show each step and what states are changing from step to step

### Turing's Hypothesis
the  concept that a single general-purpose computer can perform any computation,  and the hypothesis that all computational devices are fundamentally equivalent. 
Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 786).

Decidability - The turing machine can recognize when an input is valid and when an input is invalid thus it decides whether an input in the correct language/syntax.

Computability - "We say that a function f(x) is computable if there exists some  Turing machine such that when its tape is initialized to x, it leaves the string f(x) on  the tape."
(Sedgewick et. al (p. 787))

### Neumann architecture
where  computer programs and data are stored in the same main memory. This means  that the contents of memory can be treated as a machine instruction or data, depending on the context.
(Sedgewick et. al (p. 788))
