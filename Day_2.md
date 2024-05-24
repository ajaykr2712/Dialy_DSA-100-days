# Dialy_DSA-100-days

## Daily Log

### Day 2 - May 22, 2024

**Today's Focus:** Recursion - How it works, generalization, basic recursion, head and tail recursion

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/recursion/">GeeksforGeeks - Recursion</a>

**Activities:**
- 📝 Learned about the fundamentals of recursion and its applications.
- 📌 Practiced implementing basic recursive functions and understanding their flow.
  - 🔗 <a href="https://leetcode.com/problems/fibonacci-number/">Fibonacci Number</a>
  - 🔗 <a href="https://www.hackerrank.com/challenges/recursive-digit-sum/problem">Recursive Digit Sum</a>

**Detailed Notes:**
- 📝 Recursion:
  - **Definition**: A process in which a function calls itself as a subroutine.
  - **Generalization**: Breaking down a problem into smaller, more manageable sub-problems.
  - **Base Case**: The condition at which the recursion ends.
  - **Recursive Case**: The condition where the function continues to call itself.

- 📝 Types of Recursion:
  - **Head Recursion**: The recursive call occurs before the processing of the current function.
    ```python
    def head_recursion(n):
        if n > 0:
            head_recursion(n - 1)
            print(n)
    ```
  - **Tail Recursion**: The recursive call occurs after the processing of the current function.
    ```python
    def tail_recursion(n):
        if n > 0:
            print(n)
            tail_recursion(n - 1)
    ```

Reflections:

🤔 Recursion is a powerful tool for breaking down complex problems, but it requires careful handling of base and recursive cases to avoid infinite loops.
🚀 Understanding head and tail recursion provides insight into optimizing recursive functions, especially for converting to iterative solutions.
Next Steps:

🔜 Practice more problems involving recursion to solidify understanding.
🔜 Explore the use of recursion in data structures like trees and graphs.

**Code Snippets:**
```python
# Fibonacci Number solution in Python using recursion
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)

# Recursive Digit Sum solution in Python
def super_digit(n, k):
    def helper(x):
        if len(x) == 1:
            return int(x)
        else:
            sum_digits = sum(int(digit) for digit in x)
            return helper(str(sum_digits))

    initial_sum = str(sum(int(digit) for digit in n) * k)
    return helper(initial_sum)
