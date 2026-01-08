# Shubh-Shoppinglyx-e-commerce-website
A scalable eCommerce platform developed using Django , python , HTML , CSS , BOOTSTRAP , DRF and MySQL database and JavaScript with user authentication, cart, orders, checkout and admin control.

## 🛒 Django E-Commerce Web App

A full-featured E-Commerce web application built with Django, providing product browsing, cart management, user authentication, order placement, and profile handling.

## 🚀 Features

User Registration & Login

Product Listing by Category

Topwear

Bottomwear

Mobiles

Product Detail Page

Add to Cart / Remove from Cart

Cart Price Calculation with Shipping

Checkout & Order Placement

User Profile Management

Address Management

Mobile Filtering

By Brand (Redmi, Samsung)

By Price (Above / Below ₹10,000)

Order History

Secure routes using login_required

## 🛠️ Tech Stack

Backend: Django

Frontend: HTML, CSS, Bootstrap

Database: SQLite (default)

Authentication: Django Auth System

ORM: Django ORM



## 📂 Project Structure

project/
│
├── app/
│   ├── views.py
│   ├── models.py
│   ├── forms.py
│   ├── templates/
│   │   └── app/
│   └── static/
│
├── manage.py
└── requirements.txt


## ⚙️ Installation

Clone the repository

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Create virtual environment

python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt


Run migrations

python manage.py makemigrations
python manage.py migrate


Create superuser

python manage.py createsuperuser


Run server

python manage.py runserver


Open in browser:
👉 http://127.0.0.1:8000/
