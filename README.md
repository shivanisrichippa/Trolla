# My Shop

## Overview
My Shop is an e-commerce platform for electrical and electronics products. The application includes both user and admin panels with features such as login/signup, product listing, cart management, order placement, and payment processing using Razorpay.

## Features
### User Panel
- User authentication (Signup/Login)
- Browse and search for products
- Filter products by category
- Sort products by price (Low to High, High to Low)
- Add products to cart
- Place orders with Razorpay payment gateway

### Admin Panel
- Admin authentication (Signup/Login)
- Add, update, and delete products
- View and manage user orders

## Tech Stack
- **Frontend:** React/NextJS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **UI Library:** Material-UI
- **Authentication:** JWT
- **Payment Gateway:** Razorpay

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB (or use a cloud database like MongoDB Atlas)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd My-Shop
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory and add the required credentials (MongoDB, JWT, Razorpay keys, etc.)
4. Run the backend server:
   ```bash
   npm run server
   ```
5. Run the frontend:
   ```bash
   npm run dev
   ```
6. Open `http://localhost:4000` to view the app.

## API Endpoints
### Authentication
- `POST /api/auth/signup` - User Signup
- `POST /api/auth/login` - User Login

### Products
- `GET /api/products` - Fetch all products
- `GET /api/products/:id` - Fetch single product details
- `POST /api/products` - Add a new product (Admin only)
- `PUT /api/products/:id` - Update product details (Admin only)
- `DELETE /api/products/:id` - Delete a product (Admin only)

### Cart
- `POST /api/cart/add` - Add product to cart
- `GET /api/cart` - View cart items
- `DELETE /api/cart/remove/:id` - Remove item from cart

### Orders
- `POST /api/orders/place` - Place an order
- `GET /api/orders` - Fetch user orders
- `GET /api/orders/admin` - Fetch all orders (Admin only)

## Deployment
- The project  deployed on platform Vercel

## Demo
- User Panel: [My Shop User Panel](https://trollaprojectfrontend.vercel.app/)
- Admin Panel:[My Shop Admin Panel](https://trollaadminpanel.vercel.app/)
- A screen recording showcasing the project’s features can be provided.

## Contact
For any queries or support, reach out via email: shivanisrichippa@gmail.com

