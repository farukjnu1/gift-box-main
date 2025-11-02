🛒 E-Commerce Shopping Cart – Node.js

A Node.js web application that implements a shopping cart system for e-commerce platforms.
This project demonstrates how to manage products, add items to a cart, calculate totals, and process basic checkout functionality using Node.js, Express, and MongoDB.

-------------------------------

🏗️ Overview

The E-Commerce Shopping Cart App provides a simple but scalable solution for managing online shopping carts.
Key functionalities include:

Browsing products

Adding/removing items to/from the cart

Viewing cart summary

Calculating totals, taxes, and discounts

Checkout simulation (payment integration optional)

It is designed as a backend-driven Node.js application with RESTful APIs and a simple frontend.

-----------------------------------

🚀 Features
📦 Product Management

List products with name, price, and description

Add new products (admin only)

Edit or delete existing products

🛍️ Shopping Cart

Add/remove products from cart

Update quantity of items

Calculate total amount dynamically

Store cart in session or database

🧾 Checkout

View cart summary

Apply basic discount or tax calculation

Simulate order placement

🔧 Extensible Design

Modular architecture for controllers, routes, and models

Easy to integrate with real payment gateways (Stripe, PayPal, etc.)

--------------------------------

🧱 Technologies Used
| Category      | Technology                                                     |
| ------------- | -------------------------------------------------------------- |
| **Language**  | JavaScript (Node.js)                                           |
| **Framework** | Express.js                                                     |
| **Database**  | MongoDB / Mongoose                                             |
| **Frontend**  | EJS / HTML / CSS / Bootstrap                                   |
| **Other**     | Express-Session for cart persistence, dotenv for configuration |

------------------------------

🧠 How It Works

Product Listing:
Products are stored in MongoDB and fetched via productController.

Shopping Cart:
Items are added to cart using session storage or a Cart model in the database.

Cart Operations:
Users can increase/decrease quantities or remove items. Total is calculated dynamically.

Checkout:
Displays order summary, applies optional discounts or taxes, and simulates order placement.

------------------------------------

🔮 Future Enhancements

Add user authentication and profile-based carts

Integrate payment gateways like Stripe or PayPal

Implement inventory management

Add order history and tracking

Enhance frontend with React or Angular SPA
