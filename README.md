📚 Library Management System

A Python (Tkinter) + MySQL Desktop Application

📌 Project Overview

The Library Management System is a desktop application built using Python (Tkinter GUI) and MySQL. It automates essential library operations, including book issue/return, member management, inventory tracking, and fine calculation. The goal is to replace manual record-keeping with a reliable, user-friendly system.

🚀 Features

✔ Book Management – Add, update, delete, and search books
✔ Member Management – Maintain member records with validation
✔ Book Issue & Return – Track issue dates, due dates, and return status
✔ Automatic Fine Calculation – Auto-calculates fines for overdue books
✔ Real-Time Availability Check – Displays current stock and issued books
✔ Secure CRUD Operations – MySQL-backed data handling with error validation
✔ Intuitive Tkinter GUI – Simple, responsive, and easy to navigate

🛠️ Tech Stack

Frontend (GUI): Python Tkinter
Backend: Python
Database: MySQL
Libraries Used:

tkinter

mysql.connector

datetime

tkinter.messagebox

📂 Project Structure
├── main.py                # Application entry point  
├── database.py            # Database connection and queries  
├── gui/                   # Tkinter UI components  
├── modules/               # Issue/return logic, fine calculation  
├── assets/                # Icons, images  
└── README.md  

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/library-management-system.git
cd library-management-system

2️⃣ Install Dependencies

Ensure Python 3.x is installed.

pip install mysql-connector-python

3️⃣ Set Up MySQL Database

Create a database:

CREATE DATABASE library_db;


Import the SQL file (if you include one):

mysql -u root -p library_db < library.sql


Update your MySQL credentials inside database.py.

▶️ Run the Application
python main.py

📸 Screenshots (Optional – Add Yours)

You can include screenshots like:

Login page

Dashboard

Add book / Add member

Issue & return interface

🧠 Concepts Used

Tkinter GUI programming

MySQL CRUD operations

DSA concepts (queues, linked lists for internal logic)

Exception handling

Modular coding practices

📌 Future Enhancements

🔹 User authentication system
🔹 Export reports to Excel/PDF
🔹 Barcode scanner integration
🔹 Dark mode UI

🤝 Contribution

Contributions are welcome!
Feel free to fork this repository and submit a pull request.
