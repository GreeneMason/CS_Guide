By declaring a a key value pair one can put() an entry into a symbol table.

With the key one can get() a value from the table.

You can use hashing to provide a method of indexing the symbol table with an array of indexes.

### Example script

'''

public class *ST<Key, Value>
    *ST()                           //empty symbol table
    void put(Key key1, Value val1)  //new entry
    Value get(Key key)              //get a value
    void remove(Key key)            //remove entry
    boolean contains(Key key)       
    int size()
    Iterable<Key> keys()            //all keys in the symbol table
    
'''
Sedgewick, Robert; Wayne, Kevin. Computer Science: An Interdisciplinary Approach (p. 625).
