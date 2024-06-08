# Dialy_DSA-100-days

## Daily Log

### Day 17 - June 8, 2024

**Today's Focus:** SQL types and more about unstructured datasets

**Resources Used:**
- 📖 <a href="https://www.oreilly.com/library/view/sql-the-ultimate/9781119527074/">SQL: The Ultimate Guide by Joe Celko</a>
- 🌐 <a href="https://www.geeksforgeeks.org/sql-data-types-and-their-uses/">GeeksforGeeks - SQL Data Types</a>
- 🌐 <a href="https://www.dataversity.net/understanding-unstructured-data/">Understanding Unstructured Data</a>

**Activities:**
- 📝 Learned about different SQL data types (e.g., INT, VARCHAR, DATE)
- 📌 Explored the concept of unstructured data and its importance
  - 🔗 <a href="https://www.geeksforgeeks.org/sql-data-types-and-their-uses/">SQL Data Types</a>
  - 🔗 <a href="https://www.dataversity.net/understanding-unstructured-data/">Understanding Unstructured Data</a>

**Detailed Notes:**
- 📝 **SQL Data Types:**
  - **INT:** Used for integer values.
  - **VARCHAR:** Variable-length character strings.
  - **DATE:** Used for date values.
  - **FLOAT:** Floating point numbers.

- 📝 **Unstructured Data:**
  - Unstructured data refers to information that doesn't fit into a predefined data model or structure.
  - Examples include text files, videos, social media posts, and sensor data.

**Code Snippets:**
```sql
-- Example of creating a table with various SQL data types
CREATE TABLE example_table (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    birthdate DATE,
    salary FLOAT
);
Reflections:

🤔 Understanding different SQL data types helps in defining database schemas effectively.
🚀 Learning about unstructured data is crucial as it constitutes a significant portion of big data in real-world applications.
Next Steps:

🔜 Practice SQL queries involving various data types.
🔜 Explore methods for handling and analyzing unstructured data.

SQL data types are essential for defining the type of data that can be stored in a database column or variable. They determine how data is stored and processed within a database. Here's a comprehensive overview of SQL data types and unstructured data sets:
SQL Data Types
SQL data types can be broadly categorized into three main groups:
Numeric Data Types:
These are used to store numeric values. Examples include INT, BIGINT, DECIMAL, and FLOAT.
String Data Types:
These are used to store character strings. Examples include CHAR, VARCHAR, TEXT, and NVARCHAR.
Date and Time Data Types:
These are used to store date and time values. Examples include DATE, TIME, DATETIME, and TIMESTAMP.
Additionally, there are other data types such as:
Binary Data Types: These are used to store binary data, such as images or audio files. Examples include BLOB and BYTEA.
Boolean Data Type: This is used to store logical values (TRUE or FALSE).
Interval Data Types: These are used to store intervals of time. Examples include INTERVAL YEAR, INTERVAL MONTH, and INTERVAL DAY.
Array Data Types: These are used to store arrays of values. Examples include ARRAY and JSON.
XML Data Type: This is used to store XML data.
Spatial Data Types: These are used to store geometric or geographic data. Examples include POINT, LINE, and POLYGON.
Unstructured Data
Unstructured data refers to information that does not follow a predefined format or structure. This type of data is difficult to store and manage in traditional relational databases. Examples of unstructured data include:
Text Data: Word documents, email messages, survey responses, and social media posts.
Image and Video Data: Images, audio files, and video files.
Machine Data: Log files from websites, servers, networks, and applications, as well as data from sensors and IoT devices.
Unstructured data can be challenging to analyze and process due to its lack of structure. However, it can provide valuable insights and information when properly managed and analyzed using specialized tools and techniques.
Managing Unstructured Data
To manage unstructured data effectively, organizations use various tools and platforms that can handle the complexity and variability of this type of data. These tools enable the extraction of meaningful insights and patterns from unstructured data, which can then be used for business intelligence and analytics applications.
Some key strategies for managing unstructured data include:
Data Lakes: Centralized repositories that store raw, unprocessed data in its native format.
NoSQL Databases: Databases designed to handle unstructured data, such as document-oriented databases like MongoDB.
Data Analytics Tools: Tools like Hadoop, Spark, and machine learning algorithms that can process and analyze large volumes of unstructured data.
By understanding the characteristics of SQL data types and the complexities of unstructured data, organizations can better design and manage their databases to handle a wide range of data types and formats.