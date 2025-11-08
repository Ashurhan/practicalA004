🧩 Q1 — Sorting Algorithm Practice (Merge Sort)

Task:
Write a program to sort a list of integers using the Merge Sort algorithm.
The user enters n numbers, and your program should output them in ascending order.

Comment requirement:
Include comments in your code that:

Explain why recursion is used.

Describe how the array is divided into subarrays and how the merge process works.

Example Input:
Enter the number if elements
5

Enter the elements
8
Enter the elements
3
Enter the elements
7
Enter the elements
1
Enter the elements
4


Example Output:
1 3 4 7 8


📌 Detailed Explanation:

Why recursion is used:
Merge Sort is a divide-and-conquer algorithm. Recursion simplifies breaking the array into smaller subarrays until each contains a single element. Each recursive call handles a smaller part of the array in the same way, making the code elegant and easy to understand.

How the array is divided:

The array is split into two halves: left and right.

Each half is recursively divided until it has one element.

A single element array is considered sorted by default.

How the merge process works:

Two sorted subarrays are combined into a single sorted array.

Compare the first element of each subarray and place the smaller one into the final array.

Repeat until all elements are merged.

This ensures that after each merge, the combined array is sorted.



🧩 Q2 — Search Algorithm (Binary Search)
Task:
Implement Binary Search to find if a given number exists in a sorted array.
Ask the user for the number and display the index if found.
Comment requirement:
Describe why binary search is more efficient than linear search.


📌  Comment Requirement / Explanation:

Binary Search is more efficient than Linear Search because it repeatedly divides the search interval in half,
instead of checking each element one by one.

Linear Search checks every element sequentially → O(n) time complexity.

Binary Search reduces the search space by half each step → O(log n) time complexity.

This makes Binary Search much faster for large, sorted arrays.

Include comments in your code to explain how the middle element is chosen and how the search interval is updated.
