# Sorting Algorithms & Big O
* Sorting Algorithms
Sorting algorithms are methods or procedures used to arrange elements in a specific order, typically ascending or descending. There are various sorting algorithms, each with its advantages and disadvantages. Here, we'll discuss some popular sorting algorithms:

* Bubble Sort:
Description: Bubble sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order until the list is sorted.
Time Complexity (Average): O(n^2)

* Selection Sort:
Description: Selection sort divides the list into a sorted and an unsorted part. It repeatedly finds the smallest element in the unsorted part and swaps it with the first element of the unsorted part.
Time Complexity (Average): O(n^2)

* Insertion Sort:
Description: Insertion sort builds a sorted list one element at a time. It takes each element from the unsorted part and inserts it into the correct position in the sorted part.
Time Complexity (Average): O(n^2)

* Merge Sort:
Description: Merge sort is a divide-and-conquer algorithm that divides the list into smaller sublists, sorts them, and then merges them back together to get the final sorted list.
Time Complexity (Average): O(n log n)

* Quick Sort:
Description: Quick sort is also a divide-and-conquer algorithm. It selects a 'pivot' element and partitions the list into elements less than and greater than the pivot. It then recursively sorts the two partitions.
Time Complexity (Average): O(n log n)

* Heap Sort:
Description: Heap sort converts the list into a binary heap and then repeatedly extracts the maximum element (for ascending order) and restores the heap property.
Time Complexity (Average): O(n log n)

# Big O Notation
Big O notation is used to describe the upper bound or worst-case time complexity of an algorithm. It helps analyze how the algorithm's performance scales with the input size.

* O(1): Constant time complexity - the algorithm's execution time remains the same regardless of the input size.
* O(log n): Logarithmic time complexity - the algorithm's execution time grows logarithmically with the input size.
* O(n): Linear time complexity - the algorithm's execution time increases linearly with the input size.
* O(n log n): Log-linear time complexity - common in efficient sorting algorithms like merge sort and quicksort.
* O(n^2): Quadratic time complexity - common in inefficient sorting algorithms like bubble sort and selection sort.
* O(n^3) and beyond: Polynomial time complexity - generally found in less efficient algorithms.
* O(2^n): Exponential time complexity - extremely inefficient algorithms that grow exponentially with input size.
Understanding the time complexity of sorting algorithms helps in choosing the appropriate algorithm for specific use cases, as larger input sizes can significantly impact performance.