# Dialy_DSA-100-days

## Daily Log

### Day 12 - June 3, 2024

**Today's Focus:** Best notes on DSA, arrays, ADTs, and strings

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/data-structures/">GeeksforGeeks - Data Structures</a>
- 🌐 <a href="https://www.tutorialspoint.com/data_structures_algorithms/index.htm">TutorialsPoint - Data Structures & Algorithms</a>

**Activities:**
- 📝 Studied comprehensive notes on arrays, ADTs (Abstract Data Types), and strings.
- 📌 Summarized key concepts and definitions.

**Detailed Notes:**
- 📝 **Arrays:**
  - An array is a collection of elements identified by index or key.
  - **Operations:** Insertion, Deletion, Traversal, Searching, Sorting.
  - **Types:**
    - **1D Array:** Single row of elements.
    - **2D Array:** Matrix or table with rows and columns.
    - **Dynamic Array:** Resizable array like Python's `list`.

- 📝 **Abstract Data Types (ADTs):**
  - ADTs define a data structure purely by the operations that can be performed on it, rather than its implementation.
  - **Examples:**
    - **List:** Ordered collection with access by index.
    - **Stack:** Last-In-First-Out (LIFO) structure with `push` and `pop` operations.
    - **Queue:** First-In-First-Out (FIFO) structure with `enqueue` and `dequeue` operations.
    - **Tree:** Hierarchical structure with nodes connected by edges.

- 📝 **Strings:**
  - A string is a sequence of characters.
  - **Operations:** Concatenation, Substring, Searching, Pattern Matching.
  - **Common Algorithms:**
    - **KMP (Knuth-Morris-Pratt):** Efficient string matching algorithm.
    - **Rabin-Karp:** Uses hashing to find any one of a set of pattern strings in a text.
    - **Trie:** Tree-like data structure for efficient retrieval of strings.

**Code Snippets:**
```python
# Example: Reverse a string in Python
def reverse_string(s):
    return s[::-1]

# Example: KMP Algorithm for Pattern Matching in Python
def kmp_search(pattern, text):
    def compute_lps(pattern):
        lps = [0] * len(pattern)
        length = 0
        i = 1
        while i < len(pattern):
            if pattern[i] == pattern[length]:
                length += 1
                lps[i] = length
                i += 1
            else:
                if length != 0:
                    length = lps[length - 1]
                else:
                    lps[i] = 0
                    i += 1
        return lps

    lps = compute_lps(pattern)
    i = j = 0
    while i < len(text):
        if pattern[j] == text[i]:
            i += 1
            j += 1

        if j == len(pattern):
            return i - j
        elif i < len(text) and pattern[j] != text[i]:
            if j != 0:
                j = lps[j - 1]
            else:
                i += 1
    return -1
Reflections:

🤔 Understanding the basics and operations of arrays, ADTs, and strings is crucial for problem-solving in DSA.
🚀 Learning different algorithms and data structures helps in choosing the optimal approach for various problems.
Next Steps:

🔜 Continue practicing problems on arrays and strings.
🔜 Begin studying more complex data structures like graphs and hash tables.
