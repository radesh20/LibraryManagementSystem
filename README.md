# LibraryManagementSystem

Library Management System<img width="1463" alt="Screenshot 2024-10-02 at 1 11 02 AM" src="https://github.com/user-attachments/assets/e036f365-3dc2-447b-98f9-8b5bbf7adf3f">
<img width="1459" alt="Screenshot 2024-10-02 at 1 10 30 AM" src="https://github.com/user-attachments/assets/9b2c7f97-0ee5-4ce3-8f42-b054cca2030f">

Overview
This Library Management System is built using PHP, SQL, HTML, CSS, and JavaScript and runs on XAMPP. It provides a web-based platform for managing library resources, user accounts, and transactions. Users can log in to view and borrow books, while admins can manage the library collection and users efficiently.

Features
User Authentication:

Secure login and registration system for library users.
Admin login for library management.
Library Services:

Search for books by title, author, or category.
Borrow and return books.
View borrowing history.
Admin Dashboard:

Add, update, or delete books.
Manage user accounts.
Track borrowed and returned books.
Library Timings:

Opening: 8:00 AM
Closing: 8:00 PM
Closed on Sundays.
Library Amenities:

Free Wi-Fi.
Comfortable furniture.
Newspapers.
Discussion rooms.
RO water.
Peaceful environment.
Installation
Prerequisites
XAMPP (which includes Apache server, MySQL, and PHP)
Web browser (e.g., Chrome, Firefox)
Steps to Install
Download and Install XAMPP:

Download XAMPP from Apache Friends.
Install and start Apache and MySQL services from the XAMPP control panel.
Clone or Download the Project:

bash
Copy code
git clone https://github.com/your-username/library-management-system.git
Place the project folder inside the htdocs directory of your XAMPP installation. (Usually located at C:/xampp/htdocs on Windows).
Set Up the Database:

Open phpMyAdmin by visiting http://localhost/phpmyadmin.
Create a new database (e.g., library_db).
Import the provided SQL file (library_db.sql) to set up the database structure and initial data.
Configure the Database Connection:

Open the config.php file in the project and update the database connection details if needed:
php
Copy code
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "library_db";
Run the Application:

Open your web browser and go to http://localhost/library-management-system to access the system.
Usage
User Login: Log in using your email and password to borrow or return books.
Admin Access: Admins can manage books and users through the admin panel.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL (via XAMPP)
Web Server: Apache (via XAMPP)
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a Pull Request.
