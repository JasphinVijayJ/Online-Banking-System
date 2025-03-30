**Online Banking System**

**Overview**

The Online Banking System is a full-fledged backend application developed using Java, Spring Boot, JPA/Hibernate, MySQL, and SQL. The project is designed to manage banking operations like user registration, fund transfers, transactions, deposits, and withdrawals, along with admin functionalities for user and account management.

**Features**

User Registration

Account Dashboard

Fund Transfers Between Accounts

Transaction History

Deposit and Withdrawal Management

View All Registered Users

Delete User Accounts

Search Users by Account Number

Retrieve Transactions for Specific Users

Technologies Used

Java (Backend Development)

Spring Boot (REST API and Backend Logic)

MySQL (Database Management)

JPA/Hibernate (ORM Framework)

SQL (Database Queries)

Postman (API Testing)

**Installation**

1. Clone the repository:

git clone https://github.com/yourusername/online-banking-system.git

2. Open the project in your preferred IDE (Eclipse or Spring Tool Suite).

3. Make sure you have MySQL installed and running.

4. Create a database with the following command:

CREATE DATABASE banking_system;

5. Update the database configuration in the application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/banking_system
spring.datasource.username=root
spring.datasource.password=yourpassword

6. Run the application:

mvn spring-boot:run

7. Use Postman to test the API endpoints.

**API Endpoints**

User Registration: POST /register

View Dashboard: GET /dashboard

Fund Transfer: POST /transfer

Transaction History: GET /transactions

Deposit Money: POST /deposit

Withdraw Money: POST /withdraw

Admin: View All Users: GET /admin/users

Admin: Delete User: DELETE /admin/user/{accountNumber}
