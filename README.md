# SortMerge-Join-Database-Relation-Join-Algo
This repository contains code for SortMerge join algorithm which is one of the Database relation join algorithm. This algo is used to join two Ralation .

Project: Efficient External Sort-Merge Join Implementation

Description:
Developed a high-performance C++ program to efficiently perform external sort-merge join operations on large datasets that cannot fit into memory. The project is designed to handle database relations stored in disk files, sorting them using external merge sort and joining them using a sort-merge join algorithm.

Key Contributions:

Algorithm Design:

Implemented a two-phase external merge sort algorithm to handle large datasets by breaking them into sorted runs and then merging them.
Developed a sort-merge join method to combine two sorted relations into a single merged relation based on a common attribute.
Performance Optimization:

Used efficient data structures and algorithms to minimize disk I/O operations and optimize memory usage.
Implemented priority queues for merging sorted runs and buffers for managing I/O operations.
Technical Skills:

Extensive use of C++ features such as classes, vectors, pairs, and file handling.
Applied object-oriented principles to encapsulate the functionality of relations and join operations.
Managed memory efficiently to ensure the program can handle large datasets within limited memory constraints.
Outcome:

Successfully achieved a significant reduction in disk I/O operations, leading to improved performance for sorting and joining large datasets.
Demonstrated the ability to handle large-scale data processing tasks efficiently using advanced algorithmic techniques.
