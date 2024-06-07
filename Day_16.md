# Dialy_DSA-100-days

## Daily Log

### Day 16 - June 6, 2024

*Today's Focus:* More research on data and advanced data modeling techniques

*Resources Used:*
- 📖 <a href="https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802">The Data Warehouse Toolkit by Ralph Kimball</a>
- 🌐 <a href="https://www.coursera.org/learn/advanced-data-modeling">Coursera - Advanced Data Modeling</a>
- 🌐 <a href="https://www.geeksforgeeks.org/data-modeling-in-sql/">GeeksforGeeks - Data Modeling in SQL</a>
## The Illustration:
![image](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/4469df8d-6041-4231-8a0f-4bf97638b4f3)

*Activities:*
- 📝 Conducted extensive research on advanced data modeling techniques.
- 📌 Explored various methodologies and their applications in real-world scenarios.

*Detailed Notes:*
- 📝 *Advanced Data Modeling Techniques:*
  - *Dimensional Modeling:* Focuses on ease of data retrieval and is optimized for read-heavy operations. Commonly used in data warehouses.
    - *Star Schema:* A central fact table connected to dimension tables.
    - *Snowflake Schema:* An extension of the star schema where dimension tables are normalized.
  - *Entity-Relationship (ER) Modeling:* Focuses on the relationships between entities and is used for transactional systems.
  - *Data Vault Modeling:* Provides a more scalable and flexible approach by separating raw data, business rules, and historical data.
  - *NoSQL Data Modeling:* Adapts to non-relational databases, emphasizing flexibility and scalability. Includes key-value stores, document stores, column-family stores, and graph databases.

*Code Snippets:*
```sql
-- Example of creating a star schema in SQL
-- Fact table
CREATE TABLE Sales (
    SaleID INT PRIMARY KEY,
    DateID INT,
    ProductID INT,
    CustomerID INT,
    Amount DECIMAL(10, 2)
);

-- Dimension tables
CREATE TABLE DateDim (
    DateID INT PRIMARY KEY,
    Date DATE,
    Month INT,
    Year INT
);

CREATE TABLE ProductDim (
    ProductID INT PRIMARY KEY,
    ProductName VARCHAR(100),
    Category VARCHAR(50)
);

CREATE TABLE CustomerDim (
    CustomerID INT PRIMARY KEY,
    CustomerName VARCHAR(100),
    Location VARCHAR(100)
);
Reflections:

🤔 Understanding different data modeling techniques is crucial for designing efficient and scalable databases.
🚀 Advanced data modeling provides the foundation for building robust data architectures that support complex analytical queries and business intelligence.
Next Steps:

🔜 Implement sample data models for practical scenarios.
🔜 Practice creating and querying data models using SQL.
