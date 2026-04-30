# Algorithm-analysis-using-Big-O-notation

# Aim:
To write a program in C++ to sort a given set of elements in ascending order using the Insertion Sort algorithm (or Bubble Sort).

# Apparatus / Software Used:

Computer with C++ compiler

# Theory:

Sorting is the process of arranging data in a particular order, usually ascending or descending.
Insertion Sort is a simple sorting algorithm that builds the sorted array one element at a time.

Start from the second element, compare it with elements in the sorted portion, and insert it at the correct position.

It is in-place and stable, with time complexity:

Best Case: O(n)

Worst Case: O(n²)

Average Case: O(n²)

Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order. It continues until the array is sorted.

# Algorithm:

1.Input: Array A of n elements

2.Output: Sorted array in ascending order

3.Start from the second element (index 1).

4.Set key = A[i] (element to insert).

5.Initialize j = i - 1.

6.While j >= 0 and A[j] > key:

7.Move A[j] one position to the right (A[j + 1] = A[j])

8.Decrement j by 1 (j = j - 1)

9.Insert key at its correct position (A[j + 1] = key).

10.end 

# Conclusion:
Conclusion

The program successfully sorts the array in ascending order.

Insertion Sort is efficient for small or nearly sorted arrays.

It demonstrates the use of loops, conditional statements, and in-place sorting.

Sorting is fundamental in computer science, and understanding simple algorithms like Insertion Sort helps in learning more advanced sorting techniques.

Repeat for all elements.
