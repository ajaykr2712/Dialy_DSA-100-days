# Dialy_DSA-100-days

## Daily Log

### Day 20 - June 11, 2024

**Today's Focus:** SQL Databases and LeetCode Problems

**Resources Used:**
- 📖 <a href="https://www.w3schools.com/sql/">W3Schools - SQL Tutorial</a>
- 🌐 <a href="https://www.geeksforgeeks.org/sql-tutorial/">GeeksforGeeks - SQL Tutorial</a>

**Activities:**
- 📝 Worked on SQL databases, learning and practicing various queries.
- 📌 Solved easy to medium level questions on LeetCode related to SQL and data manipulation:
  - 🔗 <a href="https://leetcode.com/problems/combine-two-tables/">Combine Two Tables</a>
  - 🔗 <a href="https://leetcode.com/problems/employees-earning-more-than-their-managers/">Employees Earning More Than Their Managers</a>
  - 🔗 <a href="https://leetcode.com/problems/department-highest-salary/">Department Highest Salary</a>

**Detailed Notes:**
- 📝 SQL Concepts Covered:
  - **Basic Queries:** SELECT, INSERT, UPDATE, DELETE.
  - **Joins:** INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN.
  - **Aggregate Functions:** COUNT, SUM, AVG, MAX, MIN.
  - **Subqueries:** Nested queries for complex data retrieval.

**Code Snippets:**
```sql
-- Example query: Find employees earning more than their managers
SELECT e1.Name AS Employee
FROM Employee e1, Employee e2
WHERE e1.ManagerId = e2.Id AND e1.Salary > e2.Salary;
Reflections:

🤔 Practicing SQL queries on LeetCode reinforced my understanding of relational databases.
🚀 Learning to write efficient queries is essential for handling large datasets in real-world applications.
Next Steps:

🔜 Continue solving SQL problems to improve query writing skills.
🔜 Start exploring advanced SQL topics such as indexing and optimization.
