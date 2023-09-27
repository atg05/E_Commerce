# Ecommerce App

### Description

The MERN Stack E-commerce Application is a robust and feature-rich online retail platform designed to enable businesses to create and manage their e-commerce stores effectively. It provides a seamless shopping experience for users and comprehensive tools for administrators to manage products, orders, and customer interactions.

## Table of Contents

1. **Introduction**

   - Overview
   - Technologies Used

2. **Getting Started**

   - Prerequisites
   - Installation

3. **Authentication and Authorization**

   - Firebase Authentication
   - Redux Implementation
   - Server-Side Authentication Check

4. **User Management**

   - User Administration
   - Protected Routes

5. **Product Management**

   - Categories CRUD
   - Sub Categories CRUD
   - Creating Products with Categories and Sub Categories
   - Multiple Image Uploads with Client-Side Resize
   - Update and Delete Products

6. **Product Display**

   - Displaying Products with Pagination and Carousel
   - Star Rating System
   - Products Based on Categories and Sub Categories

7. **Advanced Search and Filtering**

   - Nine Different Search and Filtering Options

8. **Shopping Cart**

   - Add to Cart
   - Checkout
   - Coupon System
   - Payment with Stripe

9. **Order Management**

   - Orders
   - User Dashboard (Purchase History)
   - PDF/Invoice Download
   - Admin Dashboard (Order Management)

10. **Wishlist**

    - Adding and Managing Wishlist Items

11. **Cash On Delivery**
    - Cashless Order Processing

---

## 1. Introduction

### Overview

This documentation provides a comprehensive guide to the features and functionality of our MERN (MongoDB, Express.js, React, Node.js) stack-based e-commerce application. The app is designed for building and managing an online store with a wide range of features to enhance the user and admin experience.

### Technologies Used

- **Frontend**:

  - React for building the client-side interface
  - Firebase Authentication for user authentication
  - Redux for state management
  - Stripe for payment processing
  - Responsive design for a seamless experience on various devices

- **Backend**:
  - Node.js and Express.js for the API
  - MongoDB for the database
  - Firebase for server-side authentication
  - JWT for secure user authentication
  - Multer for image uploads
  - Stripe for handling payments

---

## 2. Getting Started

### Prerequisites

Before installing and running the application, make sure you have the following prerequisites installed on your system:

- Node.js
- MongoDB
- Firebase account for authentication
- Stripe account for payment processing

### Installation

1. Clone the repository from GitHub.

   ```bash
   git clone https://github.com/your/repo.git
   ```

2. Install server dependencies.

   ```bash
   cd server
   npm install
   ```

3. Configure Firebase and Stripe credentials.

   - In the `server/config` directory, create a `config.js` file and add your Firebase and Stripe credentials.

4. Install client dependencies.

   ```bash
   cd ../client
   npm install
   ```

5. Start the server and client.

   ```bash
   # In the server directory
   npm start

   # In the client directory
   npm start
   ```

   The application should now be running locally.

---

## 3. Authentication and Authorization

### Firebase Authentication

- User authentication is handled using Firebase Authentication.
- Users can sign up, log in, and reset their passwords securely.
- Firebase provides authentication state management.

### Redux Implementation

- Redux is used for state management, including user authentication status and user data.
- It centralizes application state and simplifies data sharing between components.

### Server-Side Authentication Check

- The server performs authentication checks to ensure that only authorized users can access protected routes.
- JWT (JSON Web Tokens) are used for secure authentication between the client and server.

---

## 4. User Management

### User Administration

- Admins can manage user accounts.
- User roles and permissions can be defined for admin-only access.

### Protected Routes

- Certain routes are protected, ensuring that only authenticated users can access them.
- Unauthorized users are redirected to the login page.

---

## 5. Product Management

### Categories CRUD

- Admins can create, read, update, and delete product categories.
- Categories help organize products effectively.

### Sub Categories CRUD

- Similar to categories, admins can manage subcategories within each category.

### Creating Products with Categories and Sub Categories

- Admins can create products and associate them with categories and subcategories.
- Products are customizable with various attributes.

### Multiple Image Uploads with Client-Side Resize

- Multiple images can be uploaded for each product.
- Client-side image resizing ensures optimal performance and storage.

### Update and Delete Products

- Admins can update product details and delete products as needed.

---

## 6. Product Display

### Displaying Products with Pagination and Carousel

- Products are displayed with pagination for a smooth browsing experience.
- A carousel component is used to showcase featured products.

### Star Rating System

- Users can rate and review products, contributing to the product's overall rating.
- Ratings and reviews are displayed on product pages.

### Products Based on Categories and Sub Categories

- Users can filter products based on categories and subcategories for a tailored shopping experience.

---

## 7. Advanced Search and Filtering

### Nine Different Search and Filtering Options

- The app provides nine different search and filtering options, including:
  - Keyword search
  - Category and subcategory filters
  - Price range filters
  - Sort by popularity, price, and rating
  - And more

---

## 8. Shopping Cart

### Add to Cart

- Users can add products to their shopping cart.
- Cart contents persist between sessions.

### Checkout

- Seamless and secure checkout process.
- Users can review and confirm their orders.

### Coupon System

- Users can apply coupon codes for discounts.

### Payment with Stripe

- Secure payment processing via Stripe integration.
- Users can pay for their orders with credit/debit cards.

---

## 9. Order Management

### Orders

- Users can view their order history.
- Admins have access to all order details.

### User Dashboard (Purchase History)

- Users can see their purchase history, order statuses, and download invoices.

### PDF/Invoice Download

- Invoices for completed orders can be downloaded in PDF format.

### Admin Dashboard (Order Management)

- Admins can manage orders, change statuses, and track order fulfillment.

---

## 10. Wishlist

### Adding and Managing Wishlist Items

- Users can add products to their wishlist for future reference.
- Wishlist items can be easily managed.

---

## 11. Cash On Delivery

### Cashless Order Processing

- Users have the option to pay using cash on delivery.
- The system handles cashless order processing, ensuring a smooth experience.
