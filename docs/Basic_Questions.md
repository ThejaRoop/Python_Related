#Code Notes


## Test Case example syntax

```

import unittest
from add_numbers import add

class TestAddNumbers(unittest.TestCase):

    def test_add_positive_numbers(self):
        result = add(3, 5)
        self.assertEqual(result, 8)  # Assert that the result is equal to 8

if __name__ == '__main__':
    unittest.main()
```
## 1. Check for Palindrome:

Write a function to determine if a given string is a palindrome (reads the same backward as forward).
## 2. Reverse a String:

Write a function to reverse a given string.
## 3. Find the Second Largest Number in a List:

Write a function to find the second largest number in a list of integers.
## 4. Merge Two Sorted Lists:

Write a function to merge two sorted lists into a single sorted list.
## 5. Remove Duplicates from a List:

Write a function to remove duplicates from a list while preserving the order of the remaining elements.
## 6. Generate Fibonacci Sequence:

Write a function to generate the Fibonacci sequence up to a given number.
## 7. Find Factorial:

Write a function to calculate the factorial of a given number.
## 8. Check for Armstrong Number:

Write a function to determine if a given number is an Armstrong number (sum of cubes of its digits equals the number itself).
## 9. Flatten a Nested List:

Write a function to flatten a nested list into a single-level list.
## 10. Swap Two Variables Without Using a Temporary Variable:

Write a function to swap two variables without using a temporary variable.
## 11. Check for Prime Number:

Write a function to determine if a given number is prime.
##  12. Implement Bubble Sort:

Write a function to implement the bubble sort algorithm.
##  13. Implement Merge Sort:

Write a function to implement the merge sort algorithm.
14. Implement Quick Sort:

Write a function to implement the quick sort algorithm.
## 15. Implement a Linked List:

Create a class to represent a linked list and implement basic operations (add, remove, search).
## 16. Implement a Stack:

Create a class to represent a stack and implement push and pop operations.
## 17. Implement a Queue:

Create a class to represent a queue and implement enqueue and dequeue operations.
## 18. Search for an Element in a Sorted Array:

Write a function to search for an element in a sorted array using binary search.
## 19. Find the Longest Common Subsequence:

Write a function to find the longest common subsequence between two strings.
## 20. Implement a Tree Traversal:

Implement at least one tree traversal algorithm (pre-order, in-order, or post-order).

##  List Manipulation:

## Reverse a given list in-place.

Example: [1, 3, 5, 2, 4] becomes [4, 2, 5, 3, 1]
```
def revlist(a):

    i,j =0,len(a) -1

    while i < j:
        a[i], a[j] = a[j], a[i]  # Swap elements at indices i and j
        print(i,j)
        i += 1
        j -= 1
        

# Example usage
test = [2]
revlist(test)  # Reverses the list in-place
print(test)  # Output: [4, 2, 5, 3, 1]
```


Find the second-largest element in a list.
Example: In [8, 2, 15, 3, 10], the second-largest is 10.
Remove duplicates from a list while preserving order.
Example: [1, 3, 3, 5, 2, 2, 4] becomes [1, 3, 5, 2, 4]
2. String Manipulation:

Check if a string is a palindrome (reads the same backward).
Example: "racecar" is a palindrome, "hello" is not.
Reverse a string in-place.
Example: "Python" becomes "nohtyP"
Identify the most frequent character in a string.
Example: In "hello world", 'l' is the most frequent.
3. Sorting:

Implement the merge sort algorithm.
Image of Merge Sort AlgorithmOpens in a new window
stackoverflow.com
Merge Sort Algorithm
Sort a list of integers using the quick sort algorithm.
Image of Quick Sort AlgorithmOpens in a new window
medium.com
Quick Sort Algorithm
4. Recursion:

Write a recursive function to calculate factorials.
factorial(5) = 5 * 4 * 3 * 2 * 1 = 120
Write a recursive function to traverse a binary tree.
Image of Binary Tree TraversalOpens in a new window
www.geeksforgeeks.org
Binary Tree Traversal
Write a recursive function to solve the Tower of Hanoi puzzle.
Image of Tower of Hanoi PuzzleOpens in a new window
www.geeksforgeeks.org
Tower of Hanoi Puzzle
5. Data Structures:

Implement a stack using a list and demonstrate its operations (push, pop, peek).
Image of Stack Data StructureOpens in a new window
www.geeksforgeeks.org
Stack Data Structure
Implement a queue using a list and demonstrate its operations (enqueue, dequeue).
Image of Queue Data StructureOpens in a new window
geeksforgeeks.org
Queue Data Structure
Implement a basic linked list and demonstrate operations (insertion, deletion, traversal).
Image of Linked List Data StructureOpens in a new window
www.geeksforgeeks.org
Linked List Data Structure
6. Algorithms:

Find the largest common divisor (GCD) of two integers using the Euclidean algorithm.
Search for a target value in a sorted list using binary search.
Check if a string contains all unique characters using a set or a loop.
7. Error Handling:

Write a function that handles division by zero using a try-except block.
Write a function that raises a custom exception if a user enters invalid input.
8. Object-Oriented Programming:

Define a class with attributes and methods to model a simple object (e.g., a car).
Implement inheritance between two classes (e.g., a base class "Animal" and a derived class "Dog").
Demonstrate polymorphism by defining a function that can work with objects of different types (e.g., a function that can print the details of any animal).


1. List Manipulation:

Reverse a given list in-place.
Find the second-largest element in a list.
Remove duplicates from a list while preserving order.
Flatten a multi-dimensional list.
Create a list of all possible combinations of elements from two lists.
Find the intersection of two lists (elements present in both).
Find the union of two lists (all unique elements from both).
Check if a list is sorted in ascending or descending order.
Shuffle a list randomly.
Create a list of prime numbers within a given range.
2. String Manipulation:

Check if a string is a palindrome.
Reverse a string in-place.
Identify the most frequent character in a string.
Remove all vowels from a string.
Count the occurrences of a specific substring within a string.
Check if two strings are anagrams of each other (same characters, different order).
Convert a string to uppercase or lowercase.
Remove all whitespace from a string.
Implement a basic string compression algorithm (e.g., run-length encoding).
3. Sorting:

Implement the merge sort algorithm.
Sort a list of integers using the quick sort algorithm.
Sort a list of strings alphabetically.
Sort a list of tuples based on a specific element within the tuples.
Sort a list in reverse order.
4. Recursion:

Write a recursive function to calculate factorials.
Write a recursive function to traverse a binary tree.
Write a recursive function to solve the Tower of Hanoi puzzle.
Write a recursive function to find the Fibonacci sequence.
Write a recursive function to generate all permutations of a string.
5. Data Structures:

Implement a stack using a list and demonstrate its operations (push, pop, peek).
Implement a queue using a list and demonstrate its operations (enqueue, dequeue).
Implement a basic linked list and demonstrate operations (insertion, deletion, traversal).
Implement a binary search tree and demonstrate operations (insertion, deletion, search).
6. Algorithms:

Find the largest common divisor (GCD) of two integers using the Euclidean algorithm.
Search for a target value in a sorted list using binary search.
Check if a string contains all unique characters using a set or a loop.
Find the first non-repeating character in a string.
Implement a basic bubble sort algorithm.


## **Arrays and Lists:**

## 1. Find the second largest element in an array.
## 2. Rotate an array to the right by a given number of steps.
## 3. Implement a function to reverse a list in-place.
## 4. Write a program to remove duplicates from a sorted list.
## 5. Given an array of integers, find a pair that sums up to a specific target.

## **Strings:**

## 6. Implement a function to check if a string is a palindrome.

```
def is_palindrome(text):
    """
    Checks if a string is a palindrome, ignoring case, spaces, and punctuation.

    Args:
        text: The string to be checked.

    Returns:
        True if the string is a palindrome, False otherwise.
    """

    text = text.lower().replace(" ", "")  # Convert to lowercase and remove spaces
    clean_text=''
    for char in text:
        if char.isalnum():
            clean_text += char
    return clean_text == clean_text[::-1]  # Compare with reversed version

# Example usage
string1 = "Racecar!"
string2 = "Hello"
string3 = "No 'x' in Nixon"
print(is_palindrome(string1))  # Output: True
print(is_palindrome(string2))  # Output: False
print(is_palindrome(string3))  # Output: True
```

## 7. Write a program to count the occurrences of each character in a string.
## 8. Reverse words in a given sentence without using library functions.
## 9. Check if two strings are anagrams of each other.
## 10. Implement a function to perform string compression, e.g., convert "aaabbbcc" to "a3b3c2".

## **Linked Lists:**

## 11. Write a function to reverse a singly linked list.
## 12. Detect if a linked list has a cycle and find the starting node of the cycle.
## 13. Merge two sorted linked lists into a single sorted list.
## 14. Remove the N-th node from the end of a linked list.
## 15. Implement a function to find the middle node of a linked list.

## **Recursion:**

## 16. Write a recursive function to calculate the factorial of a number.
## 17. Implement the Fibonacci sequence using recursion.
## 18. Write a recursive function to calculate the power of a number.
## 19. Implement the Tower of Hanoi problem using recursion.
## 20. Solve the "N Queens" problem using recursion.

## **Sorting and Searching:**

## 21. Implement the quicksort algorithm to sort an array.
## 22. Implement binary search to find an element in a sorted array.
## 23. Write a program to merge two sorted arrays into a single sorted array.
## 24. Given a rotated sorted array, find the index of a specific element.
## 25. Implement a function to find the kth largest element in an array.

## **Trees:**

## 26. Implement a binary search tree and its basic operations (insertion, deletion, searching).
## 27. Write a function to perform an in-order traversal of a binary tree.
## 28. Find the lowest common ancestor of two nodes in a binary tree.
## 29. Convert a binary search tree into a sorted doubly linked list.
## 30. Check if a binary tree is a valid binary search tree (BST).

## **Dynamic Programming:**

## 31. Implement the Fibonacci sequence using dynamic programming.
## 32. Solve the coin change problem to find the minimum number of coins needed for a target value.
## 33. Write a program to find the longest common subsequence of two strings.
## 34. Implement the knapsack problem using dynamic programming.
## 35. Find the maximum sum subarray within an array.

## **Graphs:**

## 36. Implement a graph using an adjacency matrix or adjacency list.
## 37. Write a function to perform a depth-first search (DFS) on a graph.
## 38. Implement Dijkstra's algorithm to find the shortest path in a weighted graph.
## 39. Check if a graph contains a cycle using depth-first search.
## 40. Find the connected components in an undirected graph.

