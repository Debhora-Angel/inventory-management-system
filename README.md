Inventory Management System
Overview:
The Inventory Management System is a desktop-based Sales and Inventory application developed using Python with Tkinter for the graphical user interface and SQLite for database management. The system is designed to help small businesses manage products, monitor stock levels, and handle billing operations efficiently. It provides a simple and user-friendly interface for both administrators and users.
Features:
This system includes a role-based authentication mechanism that allows secure login for Admin and User accounts. The Admin has access to product management features such as adding new products, updating existing product details, deleting products, and managing stock levels. The User role is focused on billing and sales operations, allowing product search, cart management, invoice generation, and automatic stock deduction after each transaction. The system also records transaction details including invoice number, date, and time.
Technology Stack:
The application is developed using Python as the core programming language. Tkinter is used to design and implement the graphical user interface. SQLite is used as the database for storing user credentials, product information, and sales records. The project is version-controlled using Git and hosted on GitHub.
Database Structure:
The system uses an SQLite database that contains three main tables: users, products, and sales. The users table stores login credentials and account types. The products table stores product details including product ID, name, description, category, price, and available stock. The sales table records transaction details such as transaction ID, invoice number, product ID, quantity, date, and time.
Installation and Setup:
To run this project, clone the repository to your local machine using Git. After cloning, navigate to the project directory and run the main Python file. Ensure that Python is installed on your system before executing the application. The database file is included in the repository, and the system will automatically use it when the application starts.
Default Credentials:
The system includes a default administrator account for initial access. The default username is ADMIN and the default password is ADMIN. These credentials can be modified from the database after setup.
Developer Information:
This project was developed as a desktop-based inventory and billing solution using Python and SQLite. It demonstrates practical implementation of GUI development, database integration, and role-based access control in a real-world application scenario


Execution:

python main.py


