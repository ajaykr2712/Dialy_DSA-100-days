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
