# Arrays

A data structure that uses indexing starting at 0. Each index(input) has an element(output). Very commonly used for large ammounts of data. 

## For Java
- Declare array

'int[] g;'

- Create array

'g = new int[10];'

-Initialize or populate array

'for(int i = 0; i < n; i++){
a[i] = i;
}'
 
## Syntax 
Arrays can contain any of the built in data types or custom data types but the array is limited to only one data type. The array must be declared before referncing it to avoid problems with mem-alloc.
data_type[] variable_name = new data_type[size];
Exampple;
int[] n = new int[5];

## Common problems
ArrayIndexOutOfBoundsException
This meaning that the program is refrencing an index of the array that does not exist. Sometimes this is just an error and maybe you need to adjust your loops/conditionals. But if you truly are out of an arrays space but you need it to adjust with size you will have to use/write a realloc function to change the size of the array.

## Useful snippets 
### Shuffle array
int n = deck.length;  \
for (int i = 0; i < n; i++)\
{  \
int r = i + (int) (Math.random() * (n-i));\
String temp = deck[i];  deck[i] = deck[r];\
deck[r] = temp;\
} \

Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 97). Pearson Education. Kindle Edition. 
