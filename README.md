# Gokul's Electronics Shop

## Introduction

Gokul's Electronics Shop is a fully functional e-commerce web application built with Django. It allows users to browse products, view detailed information, search for items, and add products to a shopping cart.

This project is designed with a modular architecture using Django apps, making it scalable and easy to maintain. It leverages modern web development technologies to deliver a responsive and user-friendly interface.

## Technologies Used

- **Python:** Core programming language.
- **Django:** Web framework for rapid development.
- **Bootstrap:** Front-end framework for responsive UI.
- **SQLite/PostgreSQL:** Database system.
- **Pillow:** For image handling (optional).
- **VS Code:** Code editor.
- **Git:** Version control.

## Features

- **Product Listing & Detail:** Browse products and view details.
- **Search Functionality:** Search products by name.
- **Shopping Cart:** Add, view, and remove products.
- **Responsive Design:** Mobile-friendly interface with Bootstrap.
- **Admin Panel:** Manage products and categories easily.

## Implementation Details

### Shop App

- **Models:**  
  - *Category:* Defines product categories.  
  - *Product:* Defines products with attributes like name, description, price, and image.
- **Views:**  
  - `product_list`: Displays available products with optional filtering by search or category.  
  - `product_detail`: Shows detailed information for a product.
- **Templates:**  
  - Extend a common base template with consistent styling and navigation.
- **URLs:**  
  - Routes for product listing, details, and category filtering.

### Cart App

- **Cart Logic:**  
  - Managed via Django sessions in `cart/cart.py`.
- **Views:**  
  - `cart_detail`: Displays cart contents.  
  - `cart_add` and `cart_remove`: Handle adding and removing products.
- **Templates:**  
  - A dedicated template (`cart/detail.html`) shows the cart items.
- **URLs:**  
  - Namespaced under `cart` for clear separation.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/gokuls-electronics-shop.git
   cd gokuls-electronics-shop
