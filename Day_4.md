# Dialy_DSA-100-days

## Daily Log

### Day 4 - 26-5-2024

**Today's Focus:** A quick revision about the previous days from 0 to 3, made sure I was good at all these topics

![image](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/39f438e5-34cf-4bef-be7b-6dcaf85b609a)


**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/">GeeksforGeeks</a>
- 🌐 <a href="https://leetcode.com/">LeetCode</a>
- 🌐 <a href="https://www.hackerrank.com/">HackerRank</a>
- 📖 <a href="https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850">Cracking the Coding Interview by Gayle Laakmann McDowell</a>

**Activities:**
- 📝 Reviewed array operations including insertion, deletion, and traversal.
- 📌 Revisited problems previously solved on <a href="https://leetcode.com/">LeetCode</a> and <a href="https://www.hackerrank.com/">HackerRank</a>:
  - 🔗 <a href="https://leetcode.com/problems/two-sum/">Two Sum</a>
  - 🔗 <a href="https://www.hackerrank.com/challenges/crush/problem">Array Manipulation</a>
  - 🔗 <a href="https://leetcode.com/problems/best-time-to-buy-and-sell-stock/">Best Time to Buy and Sell Stock</a>
  - 🔗 <a href="https://leetcode.com/problems/maximum-subarray/">Maximum Subarray</a>

  Sure, here are the revision notes in a concise format, focusing on the key concepts and important points without the code snippets:

# Revision Notes

## Day 1: Introduction to Arrays and Strings

### Arrays
- **Definition:** Collection of elements stored at contiguous memory locations.
- **Basic Operations:**
  - **Traversal:** Visiting each element.
  - **Insertion:** Adding an element at a specific position.
  - **Deletion:** Removing an element from a specific position.
  - **Searching:** Finding the location of an element.
  - **Updating:** Changing the value of an element.
- **Key Points:** 
  - O(1) time complexity for access.
  - Insertion and deletion can be costly (O(n) in the worst case).

### Strings
- **Definition:** Arrays of characters.
- **Common Operations:**
  - **Concatenation:** Joining two strings.
  - **Substring:** Extracting a portion of the string.
  - **Searching:** Finding a substring within a string.
  - **Replacement:** Replacing part of the string with another.

---

## Day 2: Solving Basic Problems on Arrays

### Key Problems
1. **Two Sum**
   - **Description:** Find two numbers in an array that add up to a specific target.
   - **Approach:** Use a hash map to store the difference between the target and each element.

2. **Array Manipulation**
   - **Description:** Given an array of zeros and a list of operations, add a value to each element between two given indices.
   - **Approach:** Use a difference array to efficiently handle range updates.

3. **Best Time to Buy and Sell Stock**
   - **Description:** Find the maximum profit you can achieve from buying and selling one stock.
   - **Approach:** Track the minimum price and the maximum profit possible at each step.

4. **Maximum Subarray**
   - **Description:** Find the contiguous subarray with the maximum sum.
   - **Approach:** Use dynamic programming (Kadane's algorithm) to keep track of the maximum subarray sum ending at each position.

---

## Day 3: Introduction to Linked Lists

### Linked Lists
- **Definition:** A linear data structure where elements are not stored at contiguous memory locations. Each element (node) contains a data part and a reference (or link) to the next node in the sequence.
- **Types:**
  - **Singly Linked List:** Each node points to the next node.
  - **Doubly Linked List:** Each node points to both the next and previous nodes.
  - **Circular Linked List:** The last node points back to the first node.
- **Basic Operations:**
  - **Traversal:** Visiting each node.
  - **Insertion:** Adding a new node at a specific position.
  - **Deletion:** Removing a node from a specific position.
  - **Searching:** Finding a node with a specific value.

### Key Points
- **Advantages:** Dynamic size, ease of insertion/deletion.
- **Disadvantages:** No random access (O(n) time complexity for access), higher memory usage due to storage of pointers.

**Detailed Notes:**
- 📝 Revision Summary:
  - **Day 1:** Introduction to Arrays and Strings. Key operations learned were array traversal and basic manipulations.
  - **Day 2:** Solved basic array problems to solidify understanding of the concepts learned.
  - **Day 3:** Introduction to Linked Lists, focusing on the fundamental operations and differences from arrays.

**Code Snippets:**
```python
# Revision of Two Sum solution in Python
def two_sum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in hashmap:
            return [hashmap[complement], i]
        hashmap[num] = i

# Revision of Best Time to Buy and Sell Stock solution in Python
def max_profit(prices):
    min_price = float('inf')
    max_profit = 0
    for price in prices:
        if price < min_price:
            min_price = price
        elif price - min_price > max_profit:
            max_profit = price - min_price
    return max_profit
Reflections:

🤔 Revisiting previous topics helped reinforce my understanding and identify areas where I needed further practice.
🚀 Consistent practice and revision are crucial for retaining and understanding complex concepts.
Next Steps:

🔜 Continue practicing problems related to arrays and linked lists.
🔜 Begin exploring stacks and queues in the upcoming days.
