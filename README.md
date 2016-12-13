# HeapsPython
This repository is about creating heaps in python 3. The file 'heaps.py' includes three classes:

- A 'HeapElement' class defining what a heap element shall include, at least a number - the key - and - if the user so wishes - any
kind of object containing specific information he/she might want to see carried.
- A 'MinHeap' class, where all elements in the heap are sorted into a tree whose properties are:
    - A node's key is higher than its parent's (except for the root node), and
    - A node's key is lower than any of its children's.
- A 'MaxHeap' class, creating a similar kind of tree, but with reverse properties.

Inserting, deleting an element or extracting the first element (the one with the lowest/highest key for MinHeap/MaxHeap) are
performed in O(log n) time, which is the order of magnitude of the time it takes to re-arrange the heap after those operations.
