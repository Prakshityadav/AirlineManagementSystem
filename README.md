# AirlineManagementSystem

✈️ Airline Management System

A Java-based desktop application developed using Swing and MySQL, simulating the core functionalities of an airline management platform. This system allows for managing flight details, customer records, ticket booking, and more — ideal for demonstrating Java GUI, JDBC, and database integration.
🛠️ Built With

    Java (Swing) – GUI for user interaction

    JDBC – Database connectivity

    MySQL – Backend database

    NetBeans – IDE used for development

📌 Features

✅ Admin login authentication
✅ Add / View customer details
✅ Add / View flight details
✅ Book tickets
✅ Generate boarding pass
✅ Cancel tickets
✅ Responsive and user-friendly GUI
💻 Screenshots

    (Insert screenshots of login screen, dashboard, flight booking UI, etc.)

🗄️ Database Setup

    Create a MySQL database:

CREATE DATABASE airline;

Import the required tables:

USE airline;
-- Create 'login' table
CREATE TABLE login (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(50) UNIQUE,
  password VARCHAR(50)
);

Add a test login:

    INSERT INTO login (username, password) VALUES ('admin', 'admin123');

🚀 Getting Started

    Clone the repository:

git clone https://github.com/your-username/AirlineManagementSystem.git

Open in NetBeans.

Make sure MySQL is running.

Update DB credentials in the Conn.java file:

    Connection c = DriverManager.getConnection("jdbc:mysql://localhost:3306/airline", "root", "your_password");

    Run the Login.java class to start the application.

🧑‍💻 Author

    Prakshit Yadav – GitHub Profile

