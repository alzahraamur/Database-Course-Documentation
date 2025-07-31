# Database Report

## 1. Comparison: Flat File Systems vs. Relational Databases
The table below compares Flat File Systems and Relational Databases based on several important characteristics:

| Feature           | Flat File Systems                         | Relational Databases                      |
|------------------|-------------------------------------------|-------------------------------------------|
| Structure     | Stores data in plain text files, typically one table per file. | Organized into tables with defined schemas (columns, data types). |
| Data Redundancy | High redundancy due to duplication in separate files. | Minimal redundancy using primary/foreign keys. |
| Relationships | No relationships between data entries.   | Strong support for relationships via keys. |
| Example Usage  | Simple Excel/CSV files, small local data storage. | Business systems, web applications, CRMs. |
| Drawbacks| Difficult to manage, lacks data integrity, prone to inconsistency. | More complex to set up but offers scalability and consistency. |


## 2. Mind Map: Advantages of DBMS

The following mind map illustrates the key advantages of Database Management Systems (DBMS), including Security, Integrity, Backup, Redundancy, Concurrency, and Data Sharing.

![DBMS Mind Map](advantages-dbms.png)

---

 Explanation of Each Feature:

| Feature          | Meaning in English                                             |
|------------------|----------------------------------------------------------------|
|  Security       | Protecting data from unauthorized access                      |
|  Integrity      | Ensuring data accuracy and preventing unauthorized changes    |
|  Backup         | Creating copies of data for recovery in case of loss          |
|  Redundancy     | Minimizing data duplication and storage repetition            |
|  Concurrency    | Allowing multiple users to access and modify data simultaneously |
|  Data Sharing   | Enabling multiple users or systems to access shared data      | 





## 3. Roles in a Database System

A successful database project requires collaboration between several specialized roles. Below are the main roles and their responsibilities:

 System Analyst
- Analyzes business requirements and translates them into system specifications.
- Acts as a bridge between business stakeholders and the technical team.

 Database Designer
- Designs the logical and physical structure of the database.
- Creates entity-relationship diagrams (ERDs) and defines table schemas and relationships.

 Database Developer
- Implements the database structure based on the design.
- Writes SQL queries, stored procedures, triggers, and optimizes database performance.

 Database Administrator (DBA)
- Manages and maintains the database system.
- Responsible for backup, recovery, user access control, performance tuning, and security.

 Application Developer
- Develops applications that interact with the database.
- Uses APIs, backend logic, and front-end integration to enable data operations.

 Business Intelligence (BI) Developer
- Analyzes data stored in the database to generate insights.
- Creates reports, dashboards, and visualizations to support business decision-making.
