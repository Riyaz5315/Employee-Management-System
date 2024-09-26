##
Employee Management System Using Python & MySQL<br>

Overview :-

This project is an Employee Management System built using Python and MySQL, designed to handle core employee management functions. It allows for the seamless addition, update, promotion, and deletion of employee records, with options to export employee data in PDF and Excel formats. The system is designed for ease of use, offering an interactive menu for navigating between the different features.

Features :-
1.Add Employee – Allows adding new employee details including name, email, phone number, address, position, and salary.<br>
2.Display Employee Record – Displays all employee records stored in the system.<br>
3.Update Employee Record – Provides the option to modify employee details.<br>
4.Promote Employee Record – Updates the employee’s post or salary based on promotions.<br>
5.Remove Employee Record – Deletes a selected employee’s record from the system.<br>
6.Search Employee Record – Enables searching for employee details based on various criteria.<br>
7.Export Employee Data to PDF – Exports all employee records into a PDF file.<br>
8.Export Employee Data to Excel – Exports all employee records into an Excel (.xlsx) file.<br>
9.Exit – Exits the application.<br>

##
Database Setup<br>
Before running the Employee Management System, you need to create the database and the required table in MySQL.<br>

Create the Database:<br>
CREATE DATABASE IF NOT EXISTS employee;<br>
USE employee;<br>

CREATE TABLE IF NOT EXISTS empdata (
    Id INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(100),
    Email_Id VARCHAR(100),
    Phone_no VARCHAR(15),
    Address VARCHAR(255),
    Post VARCHAR(50),
    Salary DECIMAL(10, 2)
);<br>


##
How to Run the Project<br>
Clone or download the repository to your local system.<br>
Ensure Python and MySQL are installed.<br>

Install the required Python libraries:-<br>
pip install fpdf openpyxl mysql-connector-python<br>

##
Requirements:-<br>
Python 3.x <br>
MySQL Server <br>
Python Libraries: <br>
mysql-connector-python <br>
fpdf (for PDF export) <br>
openpyxl (for Excel export) <br>








