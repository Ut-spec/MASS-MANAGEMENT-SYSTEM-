# Hostel Mess Inventory & Billing System

## 1. Problem Statement

Managing a hostel mess involves keeping track of food items, stock, student orders, and bills. Doing all this manually can cause mistakes in stock records, incorrect billing, and difficulty in checking which items are available.

The Hostel Mess Inventory & Billing System is a Java-based project developed to make these tasks easier. It helps the mess administrator manage food items and stock, while students can view the menu, place orders, and check their bills. The system also checks stock availability and records sales information.

---

## 2. Scope of the Project

This project is designed to manage the basic activities of a hostel mess using a console-based Java application.

The project includes:

* Adding and updating food items in the inventory.
* Checking available stock and item prices.
* Displaying the mess menu for students.
* Placing food orders.
* Calculating the total bill automatically.
* Checking whether enough stock is available before accepting an order.
* Maintaining student order history.
* Generating sales reports in CSV format.
* Monitoring low-stock items using a background thread.
* Storing data in an SQLite database using JDBC.
* Recording low-stock alerts in a log file.

The current project focuses on the main inventory, ordering, and billing activities of a hostel mess. Features such as online payment, student login, and a graphical user interface can be added later.

---

## 3. Target Users

### Mess Administrators

Administrators can use the system to manage food items, update stock, change prices, and generate sales reports. They can also check low-stock alerts.

### Hostel Students

Students can use the system to view the available menu, check prices, place food orders, and view their previous orders.

### Mess Management

Mess management can use the inventory and sales information to keep track of food demand and plan stock purchases.

---

## 4. High-Level Features

### Inventory Management

The admin can add new food items, update their prices and stock, and view the current inventory.

### Student Ordering

Students can browse the menu and place orders based on the available stock. The system calculates the bill automatically.

### Billing

The total amount of an order is calculated based on the items and quantities selected by the student.

### Order History

The system stores order details and allows students to check their previous orders.

### Sales Reports

The admin can generate sales reports and export them into CSV files for record keeping.

### Stock Monitoring

A background thread checks the stock levels and records alerts when an item reaches a low-stock level.

### Database Management

The application uses SQLite and JDBC to store inventory, student, and order information.

### Exception Handling

The system handles errors such as invalid quantities, insufficient stock, and missing items by displaying suitable messages.

### File Handling

CSV files are used for seed data and reports. Log files are used to store low-stock alerts.

---

## Conclusion

The Hostel Mess Inventory & Billing System is developed to make the daily work of a hostel mess easier. It combines inventory management, student ordering, billing, and sales reporting in one application. The project also uses important Java concepts such as OOP, JDBC, exception handling, file handling, and multithreading as part of the CSE2006 Java Programming syllabus.
