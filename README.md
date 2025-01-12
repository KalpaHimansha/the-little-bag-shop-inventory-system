# The Little Bag Shop - Inventory Management System

## Description  
This project implements an inventory management system for a small bag shop. It allows efficient management of bags, categories, and user roles (Cashier and Manager) using Java and SQL. The system automates inventory management, enabling shop staff to perform tasks such as adding new bags, searching by categories, and managing user accounts.

## Extended Description  
The project is designed to automate and streamline the management of a bag shop's inventory. It utilizes Object-Oriented Programming (OOP) principles in Java for user interfaces and business logic, while SQL is used to manage the underlying database of bags and users.

Key features include the ability to add, update, and delete bag records, as well as the management of user roles. The system is designed to be scalable and efficient, ensuring that the shop’s inventory and user data are well-organized.

### Challenges  
During development, several challenges were addressed:  
- **Role-Based Access Control**: Implementing two distinct user roles (Cashier and Manager) with different access levels.  
- **Database Integrity**: Ensuring that bag details and user accounts are accurately stored and managed in the database.  
- **UI/UX**: Designing a user-friendly interface for both Cashiers and Managers using Java Swing.

## Features  
- **Bag Inventory Management**: Add, update, delete, and view bag details.  
- **User Role Management**: Create new cashier accounts (Manager only).  
- **Search by Category**: Search for bags based on categories.  
- **Role-Based Access**: Different permissions for Cashiers and Managers.  
- **SQL Database**: Efficient management and retrieval of bag details and user data.

## Technologies Used  
- **Java** (Object-Oriented Programming and GUI with Swing)  
- **SQL** (Database Management for storing bag and user information)

## Setup Instructions  
To get started with the **Little Bag Shop Inventory Management System**, follow these steps:

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/little-bag-shop-inventory.git
Setup Database

Set up a local database (e.g., MySQL or PostgreSQL).
Configure the database connection in the mysql-connector-java-5.1.23-bin.jar file.
Run the Project

Open the project in your preferred IDE (e.g., Eclipse or IntelliJ IDEA).
Run the main class (Main.java) to start the application.
