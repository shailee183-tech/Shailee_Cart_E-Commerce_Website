# 🛒 ShaileeCart – Full Stack E-Commerce Website

A modern full-stack E-Commerce web application built with **React.js**, **Django REST Framework**, and **PostgreSQL**. ShaileeCart enables users to browse products, manage shopping carts, authenticate securely using JWT, and place orders through a responsive user interface.

---

## 🚀 Features

✔️ User Registration & Login

✔️ JWT Authentication & Authorization

✔️ Product Listing & Product Details

✔️ Category Management

✔️ Shopping Cart Management

✔️ Quantity Update & Item Removal

✔️ Order Creation & Checkout

✔️ Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- React Router

### Backend
- Django
- Django REST Framework

### Database
- PostgreSQL

### Authentication
- JWT (Simple JWT)

### Version Control
- Git & GitHub

---

## 📁 Project Structure

```text
ShaileeCart_E-Commerce_Website
│
├── frontend
│   ├── public
│   └── src
│       ├── assets
│       ├── components
│       ├── context
│       ├── pages
│       └── utils
│
└── backend
    ├── ecommerce
    └── products
```

---

## 🔗 API Endpoints

### Products

```http
GET /api/products/
GET /api/products/{id}/
GET /api/categories/
```

### Cart

```http
GET  /api/cart/
POST /api/cart/add/
POST /api/cart/remove/
POST /api/cart/update/
```

### Orders

```http
POST /api/orders/create/
```

### Authentication

```http
POST /api/register/
POST /api/token/
POST /api/token/refresh/
```

---

## 🏗️ Architecture

```text
React Frontend
      │
      ▼
Django REST API
      │
      ▼
JWT Authentication
      │
      ▼
PostgreSQL Database
```

---

## 🗄️ Database Entities

- User
- UserProfile
- Category
- Product
- Cart
- CartItem
- Order
- OrderItem

---

## 🎯 Objectives

- Build a modern full-stack E-Commerce platform
- Implement secure JWT-based authentication
- Integrate React frontend with Django REST APIs
- Manage products, carts, and orders efficiently
- Store and manage data using PostgreSQL

---

## 👨‍💻 Author

**Shailee Singh**

GitHub: https://github.com/shailee183-tech

---

⭐ If you found this project useful, consider giving it a star!
