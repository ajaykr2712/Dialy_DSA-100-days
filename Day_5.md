# Dialy_DSA-100-days

## Daily Log

### Day 5 - May 22, 2024

**Today's Focus:** Everything about Arrays

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/array-data-structure/">GeeksforGeeks - Arrays</a>
- 📺 <a href="https://www.coursera.org/learn/algorithms-part1">Algorithms Part I by Princeton University on Coursera</a>

**Activities:**
- 📝 Studied the introduction and declaration of arrays.
- 📝 Explored the differences between static and dynamic arrays.
- 📝 Learned about increasing array size.
- 📝 Covered 2D arrays and their applications.
- 📌 Solved array problems on various platforms:
  - 🔗 <a href="https://leetcode.com/problems/two-sum/">Two Sum</a>
  - 🔗 <a href="https://www.hackerrank.com/challenges/crush/problem">Array Manipulation</a>

**Detailed Notes:**
- 📝 **Introduction to Arrays:**
  - Arrays are a collection of elements stored at contiguous memory locations.
  - Arrays can be declared in various programming languages with fixed or dynamic sizes.
  
- 📝 **Declaration of Arrays:**
  - In Python: `arr = [1, 2, 3, 4, 5]`
  - In C: `int arr[] = {1, 2, 3, 4, 5};`
  
- 📝 **Static vs Dynamic Arrays:**
  - Static arrays have a fixed size, declared at compile time.
  - Dynamic arrays can grow in size, allowing more flexibility.
  
- 📝 **Increasing Array Size:**
  - Dynamic arrays in languages like Python use techniques like resizing (e.g., doubling the size).
  - Example in Python: `arr.append(6)` which automatically resizes if necessary.
  
- 📝 **2D Arrays:**
  - A 2D array is an array of arrays, useful for matrix operations.
  - In Python: `matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]`

**Code Snippets:**
```python
# Example of dynamic array usage in Python
arr = [1, 2, 3, 4, 5]
arr.append(6)  # Now arr is [1, 2, 3, 4, 5, 6]

# Example of 2D array
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
Reflections:

🤔 Understanding the differences between static and dynamic arrays helps in choosing the right data structure based on the use case.
🚀 The concept of 2D arrays opens up possibilities for solving complex problems involving matrices.
Next Steps:

🔜 Continue practicing array problems on LeetCode and HackerRank.
🔜 Begin learning about linked lists and their operations.
