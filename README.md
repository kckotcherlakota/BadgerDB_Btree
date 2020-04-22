# BadgerDB_Btree 
### PROJECT SUMMERY 


This project focused on implementing a B+ Tree index on a search key of integer type in a typical relation. The idea behind implementing an index is to improve performance when accessing elements in the relation. This is accomplished by storing <key,rid> pairs into the B+ Tree index. Efficient use of the B+ Tree and Buffer Manager are important to the structure and must be taken into consideration.

### instructions for 1st time run
1. cd to make directory and then do the <B>make</B>, you will see a error called <B> no .relA files, this is for second run ignore this error </B>
2. use <B>./src/badgerdb_main</B> to run the exeu file 

### instructions for 2nd time run. 
1. cd to make dir, then use <B>make clean</B>
2. then use <B>make</B> to build files 
3. use ./src/badgerdb_main to run the exeu file 


### testcases 

1. to edit test cases use main.cpp
2. to change Btree algo use BTree.cpp
