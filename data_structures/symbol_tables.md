By declaring a a key value pair one can put() an entry into a symbol table.

With the key one can get() a value from the table.

You can use hashing to provide a method of indexing the symbol table with an array of indexes.

### Example script

```

public class *ST<Key, Value>
    *ST()                           //empty symbol table
    void put(Key key1, Value val1)  //new entry
    Value get(Key key)              //get a value
    void remove(Key key)            //remove entry
    boolean contains(Key key)       
    int size()
    Iterable<Key> keys()            //all keys in the symbol table
    
```

Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 625).


### Hash table
A data structure that divides the keys into small groups that can be quickly searched.

m is used as a parameter to determine how many times the keys are divided. To divide the groups we use a hash functions which maps a key value to each entry with a number between 0 and m-1. 

After that you can perform a simple sequential search on the small groups.

The more greater m is the more memory is required but it will take less time to search.
