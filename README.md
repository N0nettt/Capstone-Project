# Lemon Web Application

![Lemon Web Application](LittleLemon/Restaurant/static/restaurant/littlelemon.png)

## Description

Lemon Web Application is a dynamic web application built using Django as part of the Meta Backend Developer Specialization. This application allows users to efficiently manage their lemonade stand business by providing features for adding new products and managing inventory. It offers a user-friendly interface tailored for both administrators and regular users.

## Features

User Authentication: Secure user registration and login functionality.
Product Management: Add, update, and delete products with details such as name, price, and description.
Inventory Tracking: Manage product inventory levels and monitor stock availability.

## Technologies Used

Django: A powerful web framework for building web applications in Python.
Python: The programming language used for backend development.
Django Rest Framework: An extension for building RESTful APIs with Django.
MySQL: A robust relational database used to store application data.
HTML, CSS, JavaScript: Frontend technologies for creating the user interface.

## Installation and Setup

Clone the repository from GitHub.
Create and activate a virtual environment.
Install the required dependencies using the following command:
bash
Copy code
pip install -r requirements.txt
Set up the MySQL database and configure the database settings in settings.py.
Apply migrations using the following command:
bash
Copy code
python manage.py migrate
Create a superuser for the Django admin:
bash
Copy code
python manage.py createsuperuser
Run the development server:
bash
Copy code
python manage.py runserver
Access the application in your web browser at http://localhost:8000/.

## Usage

Create a new account or log in if you already have one.
As an administrator, you can manage products, view sales data, and track inventory levels.
As a regular user, you can view products, add them to the cart, and place orders.
Use the search functionality to find specific products by name or description.

## License

This project is licensed under the MIT License.

Thank you for checking out the Lemon Web Application.
