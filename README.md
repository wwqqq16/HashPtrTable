# HashPtrTable - C++ Quadratic Probing Hash Table with Pointers

HashPtrTable is a C++ template class implementation of a hash table that uses quadratic probing to handle collisions. This version of the hash table stores pointers to objects in the vector, rather than storing the actual objects. Storing pointers helps save space when dealing with large objects and ensures that the table can fit within the available RAM.

## Features

- Quadratic probing to handle collisions efficiently.
- Stores pointers to objects, reducing memory usage for large objects.
- Methods for insertion, deletion, and searching for elements in the hash table.
- Destructor provided to delete valid pointers and avoid memory leaks.

## Why HashPtrTable?

The traditional QuadraticProbing hash table stores actual objects in the vector. However, when objects are more than eight bytes in size, this approach can waste significant space and even cause the table to exceed the available RAM. HashPtrTable addresses this issue by storing pointers to objects, optimizing memory usage while maintaining efficient collision handling.
