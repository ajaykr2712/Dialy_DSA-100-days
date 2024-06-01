# Dialy_DSA-100-days

## Daily Log

### Day 10 - June 1, 2024

**Today's Focus:** Revision or recap of all the topics

**Resources Used:**
- 📖 <a href="https://www.geeksforgeeks.org/data-structures/">GeeksforGeeks - Data Structures</a>
- 🌐 <a href="https://www.coursera.org/learn/algorithms-part1">Coursera - Algorithms Part I</a>
- 📘 <a href="https://www.geeksforgeeks.org/fundamentals-of-algorithms/">GeeksforGeeks - Fundamentals of Algorithms</a>
- 🌐 <a href="https://leetcode.com/">LeetCode</a>

**Activities:**
- 📝 Reviewed and recapped all topics covered so far:
  - Introduction to Data Structures and Algorithms
  - Arrays
  - Abstract Data Types (ADTs)

**Detailed Notes:**

### Introduction to Data Structures and Algorithms
- **Definition:** 
  - Data structures are ways to store and organize data to enable efficient access and modification.
  - Algorithms are step-by-step procedures or formulas for solving problems.

- **Importance:**
  - Efficient data handling and problem-solving are crucial for performance optimization in software development.

### Arrays
- **Definition:**
  - An array is a collection of items stored at contiguous memory locations.
  - The elements can be accessed randomly using indices.

- **Operations:**
  - **Insertion:** Adding an element at a specific position.
  - **Deletion:** Removing an element from a specific position.
  - **Traversal:** Accessing each element of the array sequentially.
  - **Searching:** Finding the position of an element (e.g., Linear Search, Binary Search).

- **Advantages:**
  - Simple data structure with fast access to elements.

- **Disadvantages:**
  - Fixed size, meaning the number of elements is static.
  - Insertion and deletion operations can be inefficient due to shifting elements.

- **Example Code:**
  ```python
  # Python example of array operations
  arr = [1, 2, 3, 4, 5]

  # Insertion
  arr.insert(2, 10)  # [1, 2, 10, 3, 4, 5]

  # Deletion
  arr.pop(3)  # [1, 2, 10, 4, 5]

  # Traversal
  for element in arr:
      print(element)

  # Searching
  index = arr.index(4) if 4 in arr else -1
Resources:
📖 <a href="https://www.geeksforgeeks.org/array-data-structure/">GeeksforGeeks - Arrays</a>
🌐 <a href="https://leetcode.com/tag/array/">LeetCode - Array Problems</a>
Abstract Data Types (ADTs)
Definition:

An ADT is a model for data structures that specifies the type of data stored, the operations supported, and the types of parameters of the operations.
ADTs do not specify the concrete implementation of the data structure.
Common ADTs:

List: An ordered collection of elements.
Stack: LIFO (Last In, First Out) structure.
Queue: FIFO (First In, First Out) structure.
Operations:

List: Insertion, Deletion, Traversal, Searching.
Stack: Push, Pop, Peek.
Queue: Enqueue, Dequeue, Peek.
Importance:

ADTs provide a clear and simple way to manage data.
They allow for abstraction, making it easier to manage and manipulate data without worrying about implementation details.
Resources:

📖 <a href="https://www.geeksforgeeks.org/abstract-data-types/">GeeksforGeeks - Abstract Data Types</a>
🌐 <a href="https://www.coursera.org/learn/data-structures-optimizing-performance">Coursera - Data Structures: Optimizing Performance</a>
Reflections:

🤔 Revisiting the basics of arrays and ADTs helped reinforce foundational knowledge.
🚀 Continuous practice and revision are key to mastering data structures and algorithms.
Next Steps:

🔜 Continue solving problems on arrays and ADTs on LeetCode.
🔜 Begin learning about Linked Lists.
Example Entry for Previous Days
Day 1 - [Date]
Today's Focus: Introduction to Arrays and Strings

Resources Used:

📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
🌐 <a href="https://www.geeksforgeeks.org/array-data-structure/">GeeksforGeeks - Arrays</a>
Activities:

📝 Learned about basic array operations (insertion, deletion, traversal).
📌 Solved problems on arrays from various platforms:
🔗 <a href="https://leetcode.com/problems/two-sum/">Two Sum</a>
🔗 <a href="https://www.hackerrank.com/challenges/crush/problem">Array Manipulation</a>
Detailed Notes:

📝 Arrays:
Arrays are a collection of elements stored at contiguous memory locations.
Basic operations include insertion, deletion, traversal, and searching.
Code Snippets:

python
Copy code
# Two Sum solution in Python
def two_sum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in hashmap:
            return [hashmap[complement], i]
        hashmap[num] = i
Reflections:

🤔 Understanding array manipulation is fundamental and will help in more complex data structures.
🚀 Solving problems on different platforms provided diverse perspectives on similar problems.
Next Steps:

🔜 Continue solving more array problems.
🔜 Start learning about linked lists.
