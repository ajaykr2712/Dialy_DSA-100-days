# Dialy_DSA-100-days

## Daily Log

### Day 1 - May 23, 2024

**Today's Focus:** Introduction to Stacks, Stack vs Heap Memory, Physical vs Logical Data Structures, Abstract Data Types, Time and Space Complexity

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/stack-data-structure/">GeeksforGeeks - Stack Data Structure</a>
- 🌐 <a href="https://www.geeksforgeeks.org/difference-between-stack-and-heap/">GeeksforGeeks - Difference Between Stack and Heap</a>
- 🌐 <a href="https://www.geeksforgeeks.org/data-structures-basics/">GeeksforGeeks - Data Structures Basics</a>
- 🌐 <a href="https://www.geeksforgeeks.org/abstract-data-types/">GeeksforGeeks - Abstract Data Types</a>
- 🌐 <a href="https://www.geeksforgeeks.org/analysis-of-algorithms-set-1-asymptotic-analysis/">GeeksforGeeks - Analysis of Algorithms</a>

**Activities:**
- 📝 Learned about the stack data structure, including its properties and operations.
- 📝 Studied the differences between stack and heap memory.
- 📝 Explored physical vs logical data structures.
- 📝 Understood abstract data types (ADTs).
- 📝 Reviewed time and space complexity basics.

**Detailed Notes:**
- 📝 **Stack Data Structure:**
  - A stack is a linear data structure that follows the LIFO (Last In, First Out) principle.
  - Operations: `push()`, `pop()`, `peek()`, and `isEmpty()`.
- 📝 **Stack vs Heap Memory:**
  - Stack memory is used for static memory allocation, while heap memory is used for dynamic memory allocation.
  - Stack is faster but has less space, whereas heap is slower but more flexible with larger space.
- 📝 **Physical vs Logical Data Structures:**
  - Physical data structures are the actual data storage structures like arrays and linked lists.
  - Logical data structures are the abstract forms like stacks, queues, trees, and graphs.
- 📝 **Abstract Data Types (ADTs):**
  - ADTs are a model for data types where a data type is defined by its behavior (semantics) rather than by its implementation.
### How ADT's are being leveraged: 
  ![Uploading image.png…]()

- 📝 **Time and Space Complexity:**
  - Time complexity measures the amount of time an algorithm takes to complete.
  - Space complexity measures the amount of memory an algorithm uses during its execution.

  ## Reflections:

🤔 Understanding the basics of stack operations is crucial as it is widely used in many algorithms and function call management.
🚀 Differentiating between stack and heap memory helps in optimizing memory usage and managing resource allocation better.
🤔 Knowing the difference between physical and logical data structures aids in choosing the right data structure for the right problem.
🚀 Abstract data types provide a clear understanding of data type behavior which is essential for designing efficient algorithms.
🤔 Time and space complexity analysis is fundamental to evaluating and improving algorithm performance.
Next Steps:

🔜 Continue with more stack-related problems and applications.
🔜 Begin learning about queue data structure and its operations.

**Code Snippets:**
```python
# Simple implementation of a stack in Python
class Stack:
    def __init__(self):
        self.items = []

    def is_empty(self):
        return len(self.items) == 0

    def push(self, item):
        self.items.append(item)

    def pop(self):
        if not self.is_empty():
            return self.items.pop()
        return None

    def peek(self):
        if not self.is_empty():
            return self.items[-1]
        return None

    def size(self):
        return len(self.items)

# Example usage
stack = Stack()
stack.push(1)
stack.push(2)
stack.push(3)
print(stack.pop())  # Output: 3
print(stack.peek()) # Output: 2
print(stack.size()) # Output: 2


  
