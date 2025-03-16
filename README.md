# Gokul's Electronics Shop

## Introduction

Gokul's Electronics Shop is a fully functional e-commerce web application built using Django. The platform allows users to browse a wide range of products, view detailed product information, search for items, and manage a shopping cart. The project is designed with a modular architecture using separate Django apps, ensuring scalability and ease of maintenance. It leverages modern web development technologies to deliver a responsive, user-friendly interface that is perfect for both learning and real-world deployment.

## Technologies Used

- **Python:** The core programming language.
- **Django:** The high-level web framework for rapid development.
- **Bootstrap:** A front-end framework for responsive design.
- **SQLite:** The default database for development (can be swapped with PostgreSQL for production).
- **Pillow:** (Optional) A library for handling image uploads and processing.
- **Git & GitHub:** Version control and collaborative development.
- **VS Code:** The recommended code editor.

## Features

- **Product Listing:** Browse an extensive catalog of products.
- **Product Detail Page:** View in-depth details about each product, including price and description.
- **Search Functionality:** Filter products by name using a search bar.
- **Shopping Cart:** Add, view, and remove products from your cart using Django sessions.
- **Responsive Design:** Built with Bootstrap to ensure a mobile-friendly, consistent experience across devices.
- **Admin Panel:** Use Django’s built-in admin interface for easy management of products, categories, and orders.

## Installation and Setup

### Prerequisites

- Python 3.x installed on your machine.
- pip installed.
- (Optional) A virtual environment tool (like venv).

### Clone the Repository

```bash
git clone https://github.com/yourusername/gokuls-electronics-shop.git
cd gokuls-electronics-shop
```

# Project Structure

EComm/
├── manage.py
├── my_ecommerce/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── shop/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── shop/
│           └── product/
│               ├── list.html
│               └── detail.html
└── cart/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py      # (optional, if needed)
    ├── views.py
    ├── urls.py
    ├── cart.py
    └── templates/
        └── cart/
            └── detail.html
