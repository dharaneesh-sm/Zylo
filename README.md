## 🛍️ Zylo E-Commerce Website

An online shopping platform built with the **MERN Stack**, offering a wide range of fashion, clothing, and accessories. This project provides a seamless experience for users to browse products, add them to their favorites, and make purchases. Admins can manage products effortlessly.

### 🚀 Features

- **User Authentication**: Sign up, login, and secure browsing using JWT.
- **Admin Panel**: Admins can add, update, or delete products.
- **Product Listings**: Categorized by size, gender, price, and type (clothes, accessories).
- **Favorites & Cart**: Users can save items to favorites and add to cart.
- **Order Management**: Easy checkout and order tracking for users.

### 🛠️ Tech Stack

- **MongoDB**: Database
- **Express.js**: Backend Framework
- **React.js**: Frontend Library
- **Node.js**: Server Environment

### 📑 API Endpoints

#### 🛒 Products
- `POST /products/add` – Add a new product (Admin only)
- `GET /products` – Get all products
- `GET /products/:id` – Get a specific product by ID

#### 👥 Users
- `POST /signup` – Register a new user
- `POST /signin` – Login a user

#### 🛍️ Cart
- `GET /cart` – Get all items in the cart
- `POST /cart` – Add an item to the cart
- `PATCH /cart` – Remove an item from the cart

#### 📦 Orders
- `GET /order` – Get all orders
- `POST /order` – Place a new order

#### ❤️ Favorites
- `GET /favorite` – Get all favorite items
- `POST /favorite` – Add an item to favorites
- `PATCH /favorite` – Remove an item from favorites

### 🔐 Authentication

JWT is used for securing routes like cart, orders, and favorites. Ensure valid tokens are passed for access to protected endpoints.

### 🤝 Contributing

Feel free to fork the project, make improvements, and send pull requests. Let's make shopping fun and easy for everyone!
