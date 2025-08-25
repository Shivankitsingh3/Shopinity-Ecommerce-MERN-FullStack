# Shopinity - E-Commerce Web Application

**Shopinity** is a full-featured e-commerce platform built with the **MERN stack** (MongoDB, Express, React, Node.js). It provides a smooth shopping experience with product browsing, cart functionality, checkout, payment integration, and an admin dashboard.

---

## 🛠️ Technologies Used

- **Frontend:** React.js, Redux, HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment Integration:** Razorpay, Slice
- **Deployment:** Frontend on Vercel, Backend on Render
- **Other Tools:** Git, GitHub, Postman for API testing

---

## ⚡ Features

- User authentication and profile management
- Browse and search products by category
- Add/remove products from the cart
- Checkout with Razorpay and Slice payment integration
- Admin dashboard to manage products, orders, and users
- Responsive design for mobile and desktop

---

## 📂 Project Structure

Shopinity/
│
├── backend/          # Node.js + Express server
│   ├── config/       
│   ├── controllers/  
│   ├── models/       
│   ├── routes/       
│   └── server.js     
│
├── frontend/         # React frontend for users
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Product.jsx
│   │   │   ├── Cart.jsx
│   │   │   └── Checkout.jsx
│   │   └── App.js
│   └── package.json
│
├── admin/            # React frontend for Admin Panel
│   ├── src/
│   │   ├── components/      # Reusable admin UI components
│   │   ├── pages/
│   │   │   ├── Dashboard.jsx
│   │   │   ├── ProductManagement.jsx
│   │   │   ├── OrderManagement.jsx
│   │   │   └── UserManagement.jsx
│   │   └── App.js
│   └── package.json
│
└── README.md


