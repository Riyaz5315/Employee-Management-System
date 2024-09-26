##
Employee Management System Using Python & MySQL

Overview :-

This project is an Employee Management System built using Python and MySQL, designed to handle core employee management functions. It allows for the seamless addition, update, promotion, and deletion of employee records, with options to export employee data in PDF and Excel formats. The system is designed for ease of use, offering an interactive menu for navigating between the different features.

Features :-
1.Add Employee – Allows adding new employee details including name, email, phone number, address, position, and salary.
2.Display Employee Record – Displays all employee records stored in the system.
3.Update Employee Record – Provides the option to modify employee details.
4.Promote Employee Record – Updates the employee’s post or salary based on promotions.
5.Remove Employee Record – Deletes a selected employee’s record from the system.
6.Search Employee Record – Enables searching for employee details based on various criteria.
7.Export Employee Data to PDF – Exports all employee records into a PDF file.
8.Export Employee Data to Excel – Exports all employee records into an Excel (.xlsx) file.
9.Exit – Exits the application.

##
Database Setup
Before running the Employee Management System, you need to create the database and the required table in MySQL.

Create the Database:
CREATE DATABASE IF NOT EXISTS employee;
USE employee;

CREATE TABLE IF NOT EXISTS empdata (
    Id INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(100),
    Email_Id VARCHAR(100),
    Phone_no VARCHAR(15),
    Address VARCHAR(255),
    Post VARCHAR(50),
    Salary DECIMAL(10, 2)
);


##
How to Run the Project
Clone or download the repository to your local system.
Ensure Python and MySQL are installed.

Install the required Python libraries:-
pip install fpdf openpyxl mysql-connector-python

##
Requirements:-
Python 3.x
MySQL Server
Python Libraries:
mysql-connector-python
fpdf (for PDF export)
openpyxl (for Excel export)








