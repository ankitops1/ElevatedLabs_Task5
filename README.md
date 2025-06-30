# 🔗 Task 5: SQL Joins (Inner, Left, Right, Full)

This task showcases the use of **SQL JOIN operations** to combine data from multiple related tables within an e-commerce relational database. The joins help reveal relationships between customers, orders, payments, and products.

## 🎯 Objective

Learn how to extract and combine data across two or more tables using different types of SQL joins:
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL JOIN` (simulated using `UNION` in MySQL)

## 🧱 Tables Used

- **Customers**
- **Orders**
- **Order_Items**
- **Products**
- **Payments**

## 🔁 Note: MySQL doesn’t support FULL JOIN natively. You can simulate it using UNION of LEFT JOIN and RIGHT JOIN.

## 📌 Use Case
- ✅ Retrieve customers and their orders
- ✅ Display product details with quantity ordered
- ✅ Match payments to orders and customers
- ✅ Include unmatched data using outer joins
