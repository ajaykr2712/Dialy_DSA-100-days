# Dialy_DSA-100-days

## Daily Log

### Day 9 - May 31, 2024

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

    ## Detailed Information about Arrays
Arrays are one of the most important data structures in computer science. They are widely used and provide the basis for many other data structures. Here's a deeper dive into arrays:

### What is an Array?
An array is a data structure that can hold a fixed number of elements of the same data type. Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

### Advantages of Arrays
Random Access: Elements can be accessed directly using their index.
Memory Efficiency: Arrays use a contiguous block of memory.
Ease of Traversal: Simple loops can be used to iterate through elements.
### Disadvantages of Arrays
Fixed Size: The size of an array is fixed at the time of creation.
Insertion/Deletion: Adding or removing elements can be costly, as it may require shifting elements.
Array Operations
1. Traversal
Accessing each element of the array one by one.

python
Copy code
def traverse_array(arr):
    for element in arr:
        print(element)
2. Insertion
Adding an element at a specific index.

python
Copy code
def insert_element(arr, index, element):
    arr.insert(index, element)
3. Deletion
Removing an element from a specific index.

python
Copy code
def delete_element(arr, index):
    arr.pop(index)
4. Searching
Finding the index of a specific element.

python
Copy code
def search_element(arr, element):
    for index, val in enumerate(arr):
        if val == element:
            return index
    return -1
Common Array Problems
1. Two Sum
Given an array of integers, return indices of the two numbers such that they add up to a specific target.

🔗 <a href="https://leetcode.com/problems/two-sum/">LeetCode Problem - Two Sum</a>

## python
Copy code
def two_sum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in hashmap:
            return [hashmap[complement], i]
        hashmap[num] = i
2. Best Time to Buy and Sell Stock
Find the maximum profit you can achieve from one transaction.

🔗 <a href="https://leetcode.com/problems/best-time-to-buy-and-sell-stock/">LeetCode Problem - Best Time to Buy and Sell Stock</a>

python
Copy code
def max_profit(prices):
    min_price = float('inf')
    max_profit = 0
    for price in prices:
        if price < min_price:
            min_price = price
        elif price - min_price > max_profit:
            max_profit = price - min_price
    return max_profit
3. Maximum Subarray
Find the contiguous subarray with the largest sum.

🔗 <a href="https://leetcode.com/problems/maximum-subarray/">LeetCode Problem - Maximum Subarray</a>

python
Copy code
def max_subarray_sum(nums):
    max_sum = float('-inf')
    current_sum = 0
    for num in nums:
        current_sum += num
        if current_sum > max_sum:
            max_sum = current_sum
        if current_sum < 0:
            current_sum = 0
    return max_sum
Additional Resources
📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
🌐 <a href="https://www.geeksforgeeks.org/array-data-structure/">GeeksforGeeks - Arrays</a>
📺 <a href="https://www.youtube.com/watch?v=0JUN9aDxVmI">Arrays in Data Structures - YouTube</a>
🖥️ <a href="https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/">Master the Coding Interview: Data Structures + Algorithms on Udemy</a>

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


