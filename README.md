# Library-DBMS


Here's a suggested GitHub README section for your Library DBMS project:

---

## Library Management System (DBMS Project)

### Overview
This project involves the creation of a **Library Management System** using SQL. The system is designed to handle essential library operations, including book management, customer transactions, and employee data.

### Key Features
- **Relational Database Design**: Built a 6-table relational database to manage library operations, ensuring data integrity and efficient querying.
- **Comprehensive Query Set**: Developed 10+ SQL queries to handle key functions such as checking book availability, tracking customer transactions, and managing employee data.
- **Data Integrity**: Implemented foreign keys with cascading deletes to maintain data consistency across related tables.
- **Optimized Operations**: Enhanced query performance and streamlined over 100 book transactions, improving overall system efficiency.

### Database Tables
- **Branch**: Stores branch information, including branch number, manager, address, and contact details.
- **Employee**: Tracks employee details such as ID, name, position, salary, and associated branch.
- **Customer**: Manages customer information, including registration date, address, and ID.
- **Books**: Catalogs books, including title, author, category, ISBN, and rental status.
- **IssueStatus**: Records book issuance details, linking customers to the books they borrow.
- **ReturnStatus**: Tracks book returns, ensuring the library’s inventory is up-to-date.

### SQL Queries
- **Availability Check**: Retrieve book availability based on rental status.
- **Customer Transactions**: Identify customers who have issued or returned books.
- **Employee Management**: Analyze employee salaries and their respective branch assignments.
- **Category Analysis**: Count books by category and track issuance patterns.

### Tools & Technologies
- **SQL**: Database creation, management, and querying.
- **MySQL**: RDBMS used for implementing the project.

### How to Use
1. Clone the repository and set up the MySQL database.
2. Run the SQL scripts to create tables and insert sample data.
3. Execute the provided SQL queries to perform various library management operations.

### License
This project is licensed under the MIT License.

---

This README section provides a clear and concise summary of your Library DBMS project, covering the essential aspects in a structured format.
