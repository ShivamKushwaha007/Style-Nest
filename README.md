# 🛒 StyleNest – Full Stack MERN Application

A full-featured e-commerce web application built with the MERN stack.

The platform supports secure authentication, product management, shopping cart functionality, online payments through Stripe, and an admin dashboard for managing products.

This project was built to demonstrate real-world full-stack development skills and modern web development practices.

---

## 🚀 Features

### 📦 Product Management

- Add new products
- Delete products
- Product image upload and management using Cloudinary
- Product categorization

### 🛍️ Shopping Cart Functionality

- Add products to cart
- Remove products from cart
- Update product quantity
- Persistent cart experience

### 💳 Stripe Payment Integration

- Secure online payment processing
- Real checkout workflow

### 👑 Admin Dashboard

- Manage products
- Create new products
- Delete existing products
- View store inventory

### 🛒 Cart & Checkout Process

- Smooth cart → checkout → payment flow
- Cart clearing after completed purchase

### 🔒 Security

- Authentication & authorization
- Protected user routes
- Protected admin routes
- JWT-based authentication
- Secure API access

---

## 🧰 Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Router DOM
- Zustand
- Framer Motion
- Axios

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Other Services & Tools

- Cloudinary – image storage and management
- Upstash Redis – token/session management
- Stripe – payment processing

---

## 🔐 Authentication

- User Registration
- User Login
- JWT Authentication
- Role-Based Access Control (Admin/User)
- Protected Routes

---

## 📁 Environment Variables

Create a `.env` file in the backend and add:

```env
PORT=5000

MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

CLIENT_URL=http://localhost:5173

NODE_ENV=development
```

---

## ⚙️ Installation & Setup

### Install Backend Dependencies

```bash
npm install
```

### Install Frontend Dependencies

```bash
cd frontend
npm install
```

### Run Backend

```bash
npm run dev
```

### Run Frontend

```bash
cd frontend
npm run dev
```

---

## 🚀 Build for Production

```bash
npm run build
```

### Start the Application

```bash
npm run start
```

---

## 🎯 Purpose of this Project

This project was built to:

- Practice real-world full-stack MERN development
- Implement authentication and authorization
- Integrate Stripe payment processing
- Manage product images using Cloudinary
- Build a complete e-commerce workflow
- Gain experience with state management using Zustand
- Learn production-style application architecture


