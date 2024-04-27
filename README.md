# Inventory
IMS is a web-based application built using Django, a high-level Python web framework. It provides functionalities for managing various aspects of inventory such as customers, categories, brands, suppliers, products, purchases, and orders.
Key Features
User Authentication: Allows users to register, login, and logout securely. Passwords are hashed for enhanced security.
Dashboard: Provides an overview of products, purchases, and orders, including current inventory levels.
Customer Management: Enables CRUD (Create, Read, Update, Delete) operations for managing customer information.
Category Management: Allows users to create, edit, and delete product categories.
Brand Management: Provides functionality to manage brands associated with products.
Supplier Management: Allows users to add, edit, and delete supplier information.
Product Management: Enables CRUD operations for managing products, including details like category, brand, description, quantity, price, and supplier.
Purchase Management: Facilitates the recording of product purchases from suppliers.
Order Management: Allows users to place and manage customer orders.
Setup Instructions
Clone the repository.
Install Python and Django if not already installed.
Usage Installation: Clone the repository and install dependencies using pip. bash Copy code git clone https://github.com/PrashanthBomma5/Inventory.git cd Inventory pip install -r requirements.txt
Navigate to the project directory and install dependencies using pip install -r requirements.txt.
Run migrations to create the database schema: python manage.py migrate.
Create a superuser for accessing the admin panel: python manage.py createsuperuser.
Start the development server: python manage.py runserver.
Access the application in your browser at http://localhost:8000.
Technologies Used
Python: Backend programming language.
Django: Web framework for building the application.
HTML/CSS/JavaScript: Frontend technologies for user interface and interactivity.
SQLite: Database system used for storing application data.
Contributors
Bomma Prashanth
