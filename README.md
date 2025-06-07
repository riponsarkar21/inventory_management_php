# inventory_management_php
📦 Inventory Management System – Installation Guide
This guide helps you set up and run the Inventory Management System locally using XAMPP.

✅ Requirements
XAMPP (Download from apachefriends.org)

PHP 7.4 or higher (works with PHP 8+ with minor fixes)

Web browser (e.g., Chrome, Firefox)

-----------------------------------------------------------
⚙️ Setup Instructions
1. Place the Project Files
Copy or move the unzipped project folder to:

C:\xampp\htdocs\
Example path:

C:\xampp\htdocs\inventory-management\

-----------------------------------------------------------

2. Start XAMPP
Launch XAMPP Control Panel

Start the following services:

✅ Apache

✅ MySQL
-----------------------------------------------------------

3. Create the Database
Step-by-step:
Open a browser and go to:
http://localhost/phpmyadmin
In the left sidebar, click "New".

In the "Database name" field, type:

inventory

Click "Create".

-----------------------------------------------------------
4. Import the SQL File
In phpMyAdmin, click on the inventory database you just created.

Click the "Import" tab at the top.

Click "Choose File" and select:

inventory.sql

from your project folder.

Click "Go" to import the database tables and data.

-----------------------------------------------------------
5. Run the Project
Open your browser and go to:

http://localhost/inventory-management/
You should now see the login screen or dashboard, depending on your setup.
-----------------------------------------------------------


🛠 Troubleshooting
Common Issues:
Database connection error: Make sure inventory database is created, and database_connection.php has correct MySQL credentials (usually root with no password).

PDF errors: If PDF export fails, see instructions for fixing DomPDF compatibility here.

Blank page: Check for missing include files or syntax errors. Enable error reporting in PHP.
