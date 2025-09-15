# DSA-assignment-1
To : Develop the Inventory System for a Grocery  Store

# OVERVIEW

This project implements an Inventory System for a Grocery Store using C++ with array-based data structures. It supports basic inventory operations like insertion, deletion, searching by ID or name, efficient storage using sparse representation for rarely restocked products, and organizes price and quantity data in both row-major and column-major order.

# FEATURES

* Inventory Item ADT with attributes ItemID, ItemName, Quantity, and Price.
* Insertion, deletion, and search operations.
* Use of single-dimensional array (ItemArray) for item storage.
* Management of price and quantity data using both row-major and column-major ordering.
* Sparse matrix optimization for rarely restocked products to save space.
* Console output for feedback and data display.
* Straightforward and efficient handling following DSA principles.

# PROJECT  STRUCTURE


* InventoryItem struct defining the item data.
* InventorySystem class:
  + Core methods: insertItem(), deleteItem(), searchItem(), addItemRecord(), removeItemRecord(), searchByItem().                                          
  +  Presentation methods for row-major and column-major data organization.                                                                  
  + optimizeSparseStorage() for sparse matrix representation.
* main() function contains sample test cases demonstrating functionality.

# HOW TO RUN 


* Clone the repository.
* Compile the C++ file using a C++ compiler:
* Run the executable:

# COMPLEXITY ANAYLISIS

* FUNCTION -
     + insertItem
     + deleteItem
     + searchItem
     +  Row-major and Column-major displays 
     +  Sparse Storage Output
* TIME COMPLEXITY 
     + O(1) average
     + O(n) worst-case
     + O(n)
     + O(n)
     + O(n)
     + O(n)
* SPACE COMPLEXITY
     + O(1)
     + O(1)
     + O(1)
     + O(n)
     + O(k) where k = rarely restocked count

# TECHNOLOGIES USED 

* C++ (Standard Template Library not used to focus on array implementations)
* Command Line Interface for interaction

# WORK DONE BY
NIKHIL  SACHDEVA 
BTech CSE AI/ML – Roll Number: 2401730197
