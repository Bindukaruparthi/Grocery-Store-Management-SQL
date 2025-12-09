# Grocery-Store-Management-SQL
The Grocery Store Management System is an SQL-based project designed to manage essential store operations such as product tracking, inventory management, customer and supplier records, order handling, and billing.
This project demonstrates strong database design, SQL querying, and real-world retail data management.

**Objectives**
- Efficiently manage grocery store inventory
- Maintain customer and supplier details
- Track orders and billing
- Generate sales and stock reports
- Demonstrate SQL fundamentals like joins, constraints, triggers, and views

 **Database Features**
** Tables Included**
- Products – Product ID, name, category, price, stock
- Customers – Customer name, contact, address
- Suppliers – Supplier details and product supply info
- Orders – Order details, customer, date
- Order_Items – Each product in an order
- Billing – Bill amount, tax, total
- Inventory – Stock and restock alerts


  **Project Structure**
grocery-store-management-sql/
│
├── Code/
│   └── grocery_store.sql         # Main SQL code (schema, queries, triggers)
│
├── tables/                       # Sample data tables (Excel or CSV)
│   ├── Categories.xlsx
│   ├── Customers.xlsx
│   ├── OrderDetails.xlsx
│   ├── Orders.xlsx
│   ├── Products.xlsx
│   ├── Store_Employees.xlsx
│   └── Suppliers.xlsx
│
├── README.md                     # Project description and instructions

**SQL Concepts Used**
- Table Creation: CREATE TABLE with constraints
- Data Manipulation: INSERT, UPDATE, DELETE
- Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN
- Aggregate Functions: SUM, COUNT, AVG, MAX, MIN
- Views: For reporting
- Triggers: Automatic stock updates
- Constraints: PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE, CHECK

**How to Run the Project**
1.Clone the repository
git clone https://github.com/BinduKaruparthi/grocery-store-management-sql.git
cd grocery-store-management-sql
2.Open your SQL environment (MySQL, PostgreSQL, or SQL Server)
3.Run the main SQL code
- Open Code/grocery_store.sql
- Execute all statements to create tables, insert data, and add triggers/views
4.Insert sample data
- If using Excel/CSV tables: import them into the corresponding tables
5.Run queries
- Use queries.sql or the sample queries above to test operations like reports, stock alerts, and customer orders

**Future Enhancements**
- Add stored procedures for automated billing
- Add GST and discount calculations
- Add user authentication for store employees/admin
- Connect with Python/Flask or a web UI
- Convert into a full Inventory + Billing Management System

Author
Karuparthi Bindu Padmavathi
SQL Developer | Data Analyst (Fresher)
