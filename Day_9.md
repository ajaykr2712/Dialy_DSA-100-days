# Dialy_DSA-100-days

## Daily Log

### Day 9 - May 25, 2024

**Today's Focus:** All about Arrays

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/array-data-structure/">GeeksforGeeks - Arrays</a>
- 📺 <a href="https://www.youtube.com/watch?v=0JUN9aDxVmI">Arrays in Data Structures - YouTube</a>
- 🖥️ <a href="https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/">Master the Coding Interview: Data Structures + Algorithms on Udemy</a>

**Activities:**
- 📝 Studied array basics, operations, and their time complexities.
- 📌 Solved problems involving array traversal, insertion, deletion, and searching:
  - 🔗 <a href="https://leetcode.com/problems/two-sum/">Two Sum</a>
  - 🔗 <a href="https://leetcode.com/problems/best-time-to-buy-and-sell-stock/">Best Time to Buy and Sell Stock</a>
  - 🔗 <a href="https://leetcode.com/problems/maximum-subarray/">Maximum Subarray</a>

**Detailed Notes:**
- 📝 **Array Basics:**
  - Arrays are a collection of elements stored at contiguous memory locations.
  - Each element in an array can be accessed using its index.
  - Arrays can store elements of the same data type.

- 📝 **Array Operations:**
  - **Traversal:** Accessing each element of the array.
  - **Insertion:** Adding an element at a specific index.
  - **Deletion:** Removing an element from a specific index.
  - **Searching:** Finding the index of a specific element.

- 📝 **Time Complexities:**
  - **Access:** O(1) - Direct access using index.
  - **Search:** O(n) - Linear search in the worst case.
  - **Insertion:** O(n) - Shifting elements for insertion.
  - **Deletion:** O(n) - Shifting elements for deletion.

**Code Snippets:**
```python
# Example: Two Sum solution in Python
def two_sum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in hashmap:
            return [hashmap[complement], i]
        hashmap[num] = i
Reflections:

🤔 Arrays are fundamental in computer science and understanding them is crucial for more advanced data structures.
🚀 Practicing array problems helped in grasping various operations and their complexities.
Next Steps:

🔜 Continue practicing array problems to strengthen understanding.
🔜 Start exploring more complex data structures like linked lists.
