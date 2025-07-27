# ShoppingCart-using-django
A simple yet functional Django-based shopping cart system. Users can browse products, add them to a cart, adjust quantities, view the total cost, and proceed to checkout with a confirmation page.

ShareWear Cart System is a Django-based mini e-commerce cart and checkout application that allows users to browse products, add them to their cart, manage item quantities, and proceed to checkout just like on platforms such as Amazon. It uses Django sessions to store cart data, supports quantity control (increase/decrease), displays subtotal and total dynamically, and features responsive Bootstrap UI. The system includes add-to-cart functionality, cart summary view, empty cart option, and an order confirmation page. Built using Django 5.2.4 and Bootstrap 5, it requires no user login and works entirely off session data. To get started, clone the repository, install Django in a virtual environment, run migrations, and launch the development server to begin testing. This project is ideal for beginners learning Django or for those building out a full e-commerce experience, with potential for future enhancements like user login, payment integration, and order history.

Getting Started

Clone the repository.

Create and activate a virtual environment.

Install Django: pip install django

Run migrations: python manage.py migrate

Start the development server: python manage.py runserver

Features

Add to Cart

View Cart Summary

Quantity Control (+/-)

Empty Cart

Checkout with Order Confirmation

Dynamic Total Price Calculation

Responsive UI using Bootstrap

Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap

Data Storage: Django sessions

Author

Created by Nishit Rajput as part of a college project.

Future Improvements

User authentication

Persistent carts tied to user accounts

Integration with payment gateways

Order history tracking
