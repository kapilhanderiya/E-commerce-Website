# E-Commerce Store - Full Stack Online Shopping Platform

E-Commerce Store is a full-stack web application that enables users to browse products, manage a shopping cart, apply coupons, and securely complete purchases. The platform features user authentication, an admin dashboard for product and analytics management, and robust data handling with MongoDB, Redis, and Cloudinary.


## Features

- **Product Browsing & Categories**: Explore products by category with advanced filtering and search.
- **Shopping Cart**: Add, update, or remove products from your cart with real-time price calculations.
- **Coupon System**: Apply discount codes for special offers and promotions.
- **Secure Payments**: Integrated Stripe payments for safe and reliable transactions.
- **User Authentication**: Secure signup, login, and logout with JWT-based authorization.
- **Admin Dashboard**: Manage products, categories, orders, and view sales analytics.
- **Order Management**: Track order status and history.
- **Image Uploads**: Product images are stored securely using Cloudinary.
- **Global State Management**: Zustand is used for efficient and lightweight state management.
- **Error Handling**: Comprehensive error handling for both frontend and backend.

## Tech Stack

### Frontend
- **React**: For building the user interface.
- **Vite**: For fast development and build processes.
- **TailwindCSS**: For styling.
- **Zustand**: For state management.
- **React Router**: For client-side routing.
- **Stripe.js**: For payment integration.

### Backend
- **Node.js**: For server-side logic.
- **Express**: For building RESTful APIs.
- **MongoDB**: For database storage.
- **Mongoose**: For object data modeling.
- **Redis**: For caching and session management.
- **Cloudinary**: For image storage.
- **JWT**: For secure authentication.

## Setup

### Setup .env file

```env
PORT=5000
MONGODB_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret

CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret

STRIPE_SECRET_KEY=your-stripe-secret-key
REDIS_URL=your-redis-url

NODE_ENV=development
```

### Build the app

```shell
npm run build
```
### Start the app

```shell
npm run start
```

