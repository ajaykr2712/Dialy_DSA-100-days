# Dialy_DSA-100-days

## Daily Log

### Day 3 - [Date]

**Today's Focus:** List of Sorting Algorithms and Research on Coding Questions

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844">Introduction to Algorithms by Cormen, Leiserson, Rivest, and Stein</a>
- 🌐 <a href="https://www.geeksforgeeks.org/sorting-algorithms/">GeeksforGeeks - Sorting Algorithms</a>
- 🌐 <a href="https://www.hackerrank.com/domains/tutorials/10-days-of-sorting">HackerRank - 10 Days of Sorting</a>

**Activities:**
- 📝 Compiled a list of common sorting algorithms:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
  - Counting Sort
  - Radix Sort
  - Bucket Sort
       ## An Illustrative example on how T&S Complexity are being arranged for different sorting algorithms
    ![1_ipkeWQ_Lb0lbkhB8rigxTA](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/ce19276b-2783-4de6-81c0-7a843077779e)

- 📌 Started to figure out the types of coding questions asked in interviews and competitive programming.
- 📌 Curated a list of coding questions categorized by topic:
  - Arrays
  - Strings
  - Linked Lists
  - Trees
  - Graphs
  - Dynamic Programming
  - Greedy Algorithms
  - Backtracking
- 📌 Researched the most popular coding platforms:
  - 🌐 <a href="https://leetcode.com/">LeetCode</a>
  - 🌐 <a href="https://www.hackerrank.com/">HackerRank</a>
  - 🌐 <a href="https://www.codechef.com/">CodeChef</a>
  - 🌐 <a href="https://www.codeforces.com/">Codeforces</a>

**Detailed Notes:**
- 📝 Sorting Algorithms:
  - **Bubble Sort**: Simple comparison-based algorithm. Swaps adjacent elements if they are in the wrong order. Not efficient for large datasets.
  - **Selection Sort**: Divides the array into a sorted and unsorted region. Repeatedly selects the smallest element from the unsorted region and moves it to the sorted region.
  - **Insertion Sort**: Builds the sorted array one element at a time. Picks the next element and inserts it into the correct position in the sorted part.
  - **Merge Sort**: A divide-and-conquer algorithm. Recursively divides the array into halves, sorts each half, and merges them back together.
  - **Quick Sort**: Another divide-and-conquer algorithm. Picks a pivot element, partitions the array around the pivot, and recursively sorts the partitions.
  - **Heap Sort**: Utilizes a binary heap data structure. Builds a max heap and repeatedly extracts the maximum element to build the sorted array.
  - **Counting Sort**: An integer sorting algorithm that counts occurrences of each element and uses this information to place elements in the sorted order.
  - **Radix Sort**: Non-comparative sorting algorithm. Sorts numbers digit by digit, starting from the least significant digit to the most significant digit.
  - **Bucket Sort**: Distributes elements into a number of buckets and then sorts these buckets individually.

Reflections:

🤔 Understanding the different sorting algorithms is crucial for optimizing problem-solving strategies.
🚀 Researching the types of coding questions and popular platforms provided insights into where to focus my practice efforts.
Next Steps:

🔜 Practice implementing the different sorting algorithms.
🔜 Solve categorized problems on <a href="https://leetcode.com/">LeetCode</a> and <a href="https://www.hackerrank.com/">HackerRank</a>.
🔜 Explore more advanced data structures and algorithms.

## Top Amazon Level Leet Code Questions: 
Top LeetCode questions asked in Amazon Interviews for SDE role

Number of Islands (145 times):
https://lnkd.in/dEcneG2G

Partition Labels (144 times): https://lnkd.in/dx4DN95Q

Two Sum (100 times): https://lnkd.in/dz-nQabK

Reorder Data in Log Files (89 times): https://lnkd.in/d2fGjKbv

LRU Cache (81 times): https://lnkd.in/dR5RixgJ

Minimum Difficulty of a JobSchedule
(71times): https://lnkd.in/dyCcikWr

Critical Connections in a Network (70 times): https://lnkd.in/dENuX9fh

Pairs of Songs With Total Durations Divisible by 60 (58 times): https://lnkd.in/dUHJsw7G

K Closest Points to Origin (57 times): https://lnkd.in/dFRmFD-k

Merge Two Sorted Lists (56 times): https://lnkd.in/d4_vwUni

Top K Frequent Words (55 times): https://lnkd.in/dQ2x3r2J

Copy List with Random Pointer (54 times): https://lnkd.in/dyTdBCRb

Most Common Word (49 times): https://lnkd.in/dcwBq2Ze

Merge k Sorted Lists (44 times): https://lnkd.in/dmYUdma2

Longest Palindromic Substring (43 times): https://lnkd.in/dFpK7Vbu

Subtree of Another Tree (41 times): https://lnkd.in/dtFnYKeX

Trapping Rain Water (40 times): https://lnkd.in/d6Bshc5q

Word Ladder (36 times): https://lnkd.in/ds22Z3Wg

Maximal Square (35 times): https://lnkd.in/dVejTu9G

Friend Circles (34 times): https://lnkd.in/dz9vYppU

Longest Substring Without Repeating Characters (34 times): https://lnkd.in/dAr9a5Ny

Add Two Numbers (33 times): https://lnkd.in/dC6wv5Aa

Analyze User Website Visit Pattern (31 times): https://lnkd.in/dVMTBQif

Prison Cells After N Days (31 times): https://lnkd.in/dcPywxjc

Meeting Rooms II (30 times): https://lnkd.in/dd6wGyDJ

Group Anagrams (29 times): https://lnkd.in/d9wXHgK9

Sliding Window Maximum (28 times): https://lnkd.in/djFEMnQi

Median of Two Sorted Arrays (28 times): https://lnkd.in/dtF7QHsY

Best Time to Buy and Sell Stock (28 times): https://lnkd.in/d_euBy8R

Product of Array Except Self (27 times): https://lnkd.in/ddtJrVQX

**Code Snippets:**
```python
# Example of Bubble Sort in Python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]
    return arr
