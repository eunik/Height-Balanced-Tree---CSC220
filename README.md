# Height Balanced Tree - CSC220

The purpose of this code is to sort a list using a heap binary tree.

## Running the Code

To run the code you must run with:
```
gcc HBT.c
```
This should produce an [a.exe] file.

## Executable Commands:

* i = for insert
* f = for finding root key
* l = for finding leaf key
* d = for deleting root key
* ? = for printing the tree

## Command example:

```
i 0
insert successful, key = 0, object value = 2, height is 0, and leaves is 1
?
  Checking tree
0(0)
key in root is 0, height of tree is 0, and leaves of tree is now 1
  Finished Checking tree
```
The first number is the node and the number in the paranthesis is depth (number of levels from bottom up).  
The top node is not unique, it is only a place holder. That is why you won't see the greatest root number (depth number).  
The number should be (-1000,1000)
