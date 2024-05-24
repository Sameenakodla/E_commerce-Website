E-Commerce Website
Overview
This project is an e-commerce website developed using PHP, HTML, CSS, and JavaScript. It allows users to browse products, add them to their cart, and proceed with the checkout process. The website also includes functionality for user authentication, product management, and order tracking.

Features
User Authentication: Users can create accounts, login, and logout. Passwords are securely hashed and stored in the database.
Product Browsing: Users can browse through a list of available products, view detailed product information, and add products to their shopping cart.
Shopping Cart: Users can add and remove products from their shopping cart. The cart is stored in the user's session.
Checkout Process: Users can proceed with the checkout process, entering their shipping address and payment details.
Order Management: Admin users have access to an admin panel where they can manage products, view orders, and update order statuses.
Installation
Clone the repository: git clone https://github.com/your-username/e-commerce.git
Navigate to the project directory: cd e-commerce
Import the database schema from database/schema.sql into your MySQL database.
Configure the database connection in config/database.php.
Start a PHP server: php -S localhost:8000
