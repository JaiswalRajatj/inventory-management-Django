# Inventory Management System - Django

## Introduction

The Inventory Management System is a robust web application built with Django. It allows businesses and individuals to efficiently manage inventory, track product stock, handle suppliers and customers, and analyze sales and purchase transactions. The project is designed for ease of use, providing a clean interface and essential features for day-to-day inventory operations.

## Features

- User authentication with login/logout functionality.
- Dashboard overview with key statistics.
- Add, edit, and delete products, categories, and brands.
- Track inventory levels and manage stock.
- Record and manage sales and purchase transactions.
- Customer and supplier management.
- Search and filtering for products and transactions.
- Export data to CSV for reporting and analysis.
- Responsive design for desktop and mobile devices.

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- Python 3.7+
- pip (Python package manager)
- Git

### Steps

1. **Clone the Repository**
   - Clone the project to your local machine using:
     ```bash
     git clone https://github.com/JaiswalRajatj/inventory-management-Django.git
     cd inventory-management-Django
     ```

2. **Create and Activate Virtual Environment**
   - (Optional but recommended) Create a virtual environment:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       venv\Scripts\activate
       ```
     - On macOS/Linux:
       ```bash
       source venv/bin/activate
       ```

3. **Install Dependencies**
   - Install the required packages using pip:
     ```bash
     pip install -r requirements.txt
     ```

4. **Apply Migrations**
   - Set up the database by running:
     ```bash
     python manage.py migrate
     ```

5. **Create a Superuser**
   - Create an admin account to access the Django admin interface:
     ```bash
     python manage.py createsuperuser
     ```

6. **Run the Development Server**
   - Start the local server:
     ```bash
     python manage.py runserver
     ```
   - Access the application at `http://127.0.0.1:8000/`.

7. **Access the Admin Panel**
   - Visit `http://127.0.0.1:8000/admin/` and log in with the superuser credentials to manage products, categories, brands, users, and more.

---

For further customization, deployment instructions, or contributing guidelines, please refer to the repository's documentation or open an issue for help.
