# Dialy_DSA-100-days

## Daily Log

### Day 15 - June 6, 2024

**Today's Focus:** Moving on to some SQL and things related to database administration

**Resources Used:**
- 📖 <a href="https://www.amazon.com/Learning-SQL-Alan-Beaulieu/dp/0596520832">Learning SQL by Alan Beaulieu</a>
- 🌐 <a href="https://www.w3schools.com/sql/">W3Schools - SQL Tutorial</a>
- 🌐 <a href="https://www.sqltutorial.org/">SQL Tutorial</a>

**Activities:**
- 📝 Learned about basic SQL commands and their uses
- 📌 Practiced writing SQL queries to create, read, update, and delete records
  - 🔗 <a href="https://leetcode.com/problems/combine-two-tables/">Combine Two Tables</a>
  - 🔗 <a href="https://leetcode.com/problems/customers-who-never-order/">Customers Who Never Order</a>

**Detailed Notes:**
- 📝 SQL Basics:
  - **CREATE TABLE:** Used to create a new table in the database.
  - **INSERT INTO:** Used to insert new records into a table.
  - **SELECT:** Used to query and read data from a table.
  - **UPDATE:** Used to modify existing records in a table.
  - **DELETE:** Used to delete records from a table.

```sql
-- Example: Creating a new table
CREATE TABLE Employees (
    EmployeeID int,
    FirstName varchar(255),
    LastName varchar(255),
    BirthDate date,
    Position varchar(255)
);

-- Example: Inserting a record into the table
INSERT INTO Employees (EmployeeID, FirstName, LastName, BirthDate, Position)
VALUES (1, 'John', 'Doe', '1980-01-01', 'Manager');

-- Example: Querying data from the table
SELECT * FROM Employees;

-- Example: Updating a record in the table
UPDATE Employees
SET Position = 'Senior Manager'
WHERE EmployeeID = 1;

-- Example: Deleting a record from the table
DELETE FROM Employees
WHERE EmployeeID = 1;
Reflections:

🤔 Understanding the fundamentals of SQL is essential for effective database management.
🚀 Practicing SQL queries helps in getting a better grasp of data manipulation and retrieval.
Next Steps:

🔜 Continue practicing more complex SQL queries.
🔜 Learn about advanced topics in SQL like joins, indexing, and transactions.
