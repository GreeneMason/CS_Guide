### Definitions
alphabet - finite set of symbols

string - a finite sequence of ahlphabet symbols

formal language - (can be infinite) set of strings all over the same alphabet

Specification problem - Its difficult to completely and precisely define a complete formal language

Recognition problem - Recognizing all possible strings within an alphabet is also difficult

Regular Expressions(RE) - A string of symbols that specifies a formal language.

Regular language - A language that can be specified by a regular expression.

Generalized RE's - Can be used to describe regular language. (Expand the alphabet, Shorthand for union, extensions to the closure operation)

Abstract machines - A model of computation for the formal language recognition problem. Indicates whether the input was valid or invalid.

### Deterministic finite-state autamata
 - A finite number of states
 - A set of transitions
 - A tape reader

### Nondeterministic finite state automata
 - Multiple transitions labeled with the same symbol is allowed
 - Unlabled state transitions (null transitions) are allowed
 - Not all symbols are required for the transitions leaving each state

### Theorem. 
(Kleene, 1951) REs, DFAs, and NFAs are equivalent models, in the  sense that they all characterize the regular languages. 
Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 748).
