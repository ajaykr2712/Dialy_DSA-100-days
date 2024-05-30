# Dialy_DSA-100-days

## Daily Log

### Day 8 - May 24, 2024

**Today's Focus:** Everything about Array ADTs and list of all searches

**Resources Used:**
- 📖 <a href="https://www.youtube.com/playlist?list=PLl0KD3g-oDOGJUdmhFk19LaPgrfmAGQfo">YouTube Lectures by Abdul Bari</a>

**Activities:**
- 📝 Studied Array Abstract Data Types (ADTs)
- 📌 Reviewed various search algorithms

**Detailed Notes:**
- 📝 **Array ADTs:**
  - Arrays are a collection of elements identified by index or key.
  - Operations include traversal, insertion, deletion, and searching.

- 📝 **Search Algorithms:**
  - **Linear Search:**
    - Iterates through each element to find the target value.
    - Time complexity: O(n)
  - **Binary Search:**
    - Efficient for sorted arrays by repeatedly dividing the search interval in half.
    - Time complexity: O(log n)
  - **Jump Search:**
    - Jumps ahead by fixed steps and then performs a linear search within the block.
    - Time complexity: O(√n)

**Code Snippets:**
```python
# Example code for Linear Search
def linear_search(arr, target):
    for i in range(len(arr)):
        if arr[i] == target:
            return i
    return -1

# Example code for Binary Search
def binary_search(arr, target):
    low, high = 0, len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return -1
Reflections:

🤔 Understanding the basics of Array ADTs is crucial for various data structure implementations.
🚀 Practicing different search algorithms helped solidify the concepts and their applications.
Next Steps:

🔜 Continue practicing array problems on different platforms.
🔜 Start learning about linked lists and their operations.
