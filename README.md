Personal Finance Manager
Overview
The Personal Finance Manager is a project aimed at helping individuals track and manage their financial life. This application will allow users to log their expenses, income, track financial goals, and generate reports for better financial planning.

This project will use modern technologies such as Java, Spring Boot, MySQL, and Spring Data JPA to build a full-fledged application for personal finance management.

Technologies Used
Java 17: The core programming language for implementing the business logic.

Spring Boot 3.3.11: Framework used for building the backend of the application.

MySQL: Relational database to store user data, expenses, income, and transactions.

Spring Data JPA: A library that simplifies database operations in the Spring environment.

H2 (optional): For development and testing purposes.

Maven: Project management and dependency management tool.

Features
User Registration & Authentication:

Users can create an account and log in to manage their financial data securely.

Expense & Income Tracking:

Users can log their expenses and income by category, date, and amount.

Financial Goal Setting:

Users can set short-term or long-term financial goals (e.g., saving for a vacation, paying off debt) and track their progress.

Reports & Insights:

Generate reports to view monthly and yearly spending, income, and savings.

Graphical insights for better visualization.

Day 1 Progress
Setup
Environment setup:

Installed Spring Boot with Java 17.

Installed and configured MySQL database for storing user and financial data.

Configuration
Spring Boot Project:

Initialized the project using Spring Initializr with dependencies for Spring Web, Spring Data JPA, and MySQL.

Set up application.properties to configure MySQL connection.

Database:

Created the necessary MySQL database and configured the connection details in the Spring Boot application.

Set up Spring Data JPA for ORM-based database interaction.

Testing
Successfully ran the application, and the Spring Boot server started on port 8080.

Connected to the MySQL database and verified the connection.

Next Steps
User Authentication:

Implement user registration and login functionality using Spring Security.

Expense and Income Management:

Build features to add, edit, and delete expenses and income.

Database Design:

Design the necessary database tables to store user data, transactions, goals, etc.

Reports & Insights:

Start implementing financial reports and visual charts for insights.