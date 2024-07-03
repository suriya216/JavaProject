# Student Management System

A Java application to manage student records, utilizing JDBC for database connectivity and MySQL as the database.

## **Overview**

The Student Management System is a simple Java application designed to perform CRUD (Create, Read, Update, Delete) operations on student records stored in a MySQL database. This project demonstrates the use of JDBC for database connectivity and basic SQL operations.

## Features

- Add new student records
- View all student records
- Update existing student records
- Delete student records

### Prerequisites

- Java Development Kit (JDK) 8 or later
- MySQL Database
- JDBC Driver for MySQL

# Installation

### Clone the repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

### Configure the database connection

Edit the `db.properties` file to include your MySQL database credentials

```
jdbc.url=jdbc:mysql://localhost:3306/student_db
jdbc.username=your-username
jdbc.password=your-password
jdbc.driverClassName=com.mysql.cj.jdbc.Driver
```

# Usage

### Run the application

```bash
java -cp .:mysql-connector-java-8.0.23.jar Main
```

Follow the on-screen prompts to perform various operations

# Database Schema

The database contains a single table `students` with the following structure:

| Column | Type | Description |
| --- | --- | --- |
| id | INT | Primary key |
| name | VARCHAR(100) | Name of the student |
| grade | VARCHAR(100) | Grade of the student |
| age | INT | Age of the student |

The database contains a single table `department`with the following structure:

| Column | Type | Description |
| --- | --- | --- |
| departmentName | VARCHAR(100) | Primary key |
| id | INT | Foreign key |
| name | VARCHAR(100) | Name of the student |

# Contact

For any questions or suggestions, feel free to contact me at sssuriya003@gmail.com.
