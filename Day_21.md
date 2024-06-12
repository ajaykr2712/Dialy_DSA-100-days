# Dialy_DSA-100-days

## Daily Log

### Day 21 - June 12, 2024

**Today's Focus:** Worked on SQL databases and backend stacks

**Resources Used:**
- 📖 <a href="https://www.w3schools.com/sql/">W3Schools - SQL Tutorial</a>
- 🌐 <a href="https://www.udemy.com/course/the-complete-sql-bootcamp/">The Complete SQL Bootcamp on Udemy</a>
- 📖 <a href="https://www.postgresql.org/docs/">PostgreSQL Official Documentation</a>

**Activities:**
- 📝 Enhanced knowledge on SQL databases, focusing on queries, joins, and indexing.
- 📌 Worked on backend stacks, including database integration and API development.

**Detailed Notes:**
- 📝 SQL Databases:
  - **Queries:** Learned advanced querying techniques, including nested queries and subqueries.
  - **Joins:** Practiced different types of joins (INNER, LEFT, RIGHT) to combine data from multiple tables.
  - **Indexing:** Understood the importance of indexing for optimizing query performance.
  
- 📝 Backend Stacks:
  - Integrated SQL databases with backend applications.
  - Developed RESTful APIs to interact with the database.

**Code Snippets:**
```python
# Example of an SQL query with a join
SELECT employees.name, departments.name
FROM employees
INNER JOIN departments
ON employees.department_id = departments.id;

# Example of a simple API endpoint in Python (Flask)
from flask import Flask, jsonify, request
import psycopg2

app = Flask(__name__)

@app.route('/employees', methods=['GET'])
def get_employees():
    conn = psycopg2.connect("dbname=test user=postgres password=secret")
    cur = conn.cursor()
    cur.execute("SELECT * FROM employees;")
    employees = cur.fetchall()
    cur.close()
    conn.close()
    return jsonify(employees)

if __name__ == '__main__':
    app.run(debug=True)
Reflections:

🤔 Understanding the interplay between SQL databases and backend development is crucial for building efficient applications.
🚀 Learning how to optimize queries and properly integrate databases with backend services enhances overall application performance.
Next Steps:

🔜 Continue practicing advanced SQL queries.
🔜 Focus on implementing more complex backend functionalities.
