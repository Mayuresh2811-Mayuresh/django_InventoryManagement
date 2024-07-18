# Django Inventory Management System

A simple and efficient inventory management system built with Django. This project helps to manage the stock of items, track inventory levels, and ensure smooth operations for managing products.

## Features

- Add, edit, delete, and view items.
- Track inventory levels.
- Search for specific items.
- User authentication for secure access.
- Simple and intuitive user interface.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your computer.
- Django 3.x installed. If not, you can install it using the following command:
  ```sh
  pip install django

## Installation
Clone the Repository



git clone https://github.com/Mayuresh2811-Mayuresh/django_InventoryManagement.git
cd django_InventoryManagement

## Create a Virtual Environment


python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

## Install Dependencies


pip install -r requirements.txt

## Apply Migrations


python manage.py migrate

## Create a Superuser


python manage.py createsuperuser

## Run the Server

python manage.py runserver
Access the Application

Open your web browser and go to http://127.0.0.1:8000.

Usage
Admin Interface: Log in to the admin site at http://127.0.0.1:8000/admin using the superuser credentials you created.
Manage Inventory: Use the admin interface to add, edit, delete, and view items in the inventory.
