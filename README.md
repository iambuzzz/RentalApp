# Rental Management System (MERN Stack)

A full-stack rental management application built for the Odoo Hackathon. This platform serves as a two-sided marketplace, allowing **Lenders** to list products for rent and **Customers** to browse, request quotations, and rent items through a complete order fulfillment workflow.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)

---

### 🔴 Live Demo

**[View the live application here]** `[https://rentalapp-szo5.onrender.com/]`

---

## 📸 Screenshots

| Customer Shop Page | Lender Dashboard | Quotation Detail |
| :---: | :---: | :---: |
| `[YOUR_SCREENSHOT_HERE]` | `[YOUR_SCREENSHOT_HERE]` | `[YOUR_SCREENSHOT_HERE]` |

---

## ✨ Key Features

This application is divided into two main user roles, Customer and Lender, each with its own set of features.

### 👤 Customer Features
* **Authentication:** Secure JWT-based registration, login, and password reset (via OTP).
* **Product Browsing:** View all listed products with search, sorting, and category filtering.
* **Quotation System:** Instead of a simple "buy," customers request a quotation by selecting products, rental dates, and a delivery method (self-pickup or home delivery).
* **Order Tracking:** A dedicated "My Orders" page to track the status of all rentals (`Pending`, `Quotation Approved`, `Reserved`, `Payment Request`, `PickedUp`, `Returned`).
* **Interactive Workflow:** Customers can "Accept" approved quotations to reserve an item.
* **Payment:** A dedicated payment page to pay for reserved items.
* **Profile Management:** Customers can edit their profile details and change their password.
* **Wishlist:** Save products for later.

### 💼 Lender Features
* **Authentication:** Separate login for the lender role.
* **Dynamic Dashboard:** A comprehensive dashboard with live analytics on revenue, total rentals, top products, and top customers. All data is filterable by date and searchable.
* **Product Management:** Full CRUD (Create, Read, Update, Delete) functionality for product listings. Lenders set custom price lists (hourly, daily, weekly) and pickup addresses.
* **Quotation Management:** A "Rental" page to view and manage all active quotations.
* **Full Rental Lifecycle:** Lenders can "Approve" new requests, "Request Payment" for reserved items, and "Mark as Returned" to complete an order.
* **Order History:** A separate "Orders" page to view all completed and returned rentals.
* **Profile Management:** Lenders can edit their profile details and change their password.

---

## 🛠 Tech Stack

### Backend (`server`)
* **[Node.js](https://nodejs.org/)**: JavaScript runtime environment.
* **[Express.js](https://expressjs.com/)**: Backend web framework.
* **[MongoDB](https://www.mongodb.com/)**: NoSQL database for storing user, product, and quotation data.
* **[Mongoose](https://mongoosejs.com/)**: Object Data Modeling (ODM) library for MongoDB.
* **[JWT (jsonwebtoken)](https://jwt.io/)**: For secure user authentication and route protection.
* **[bcrypt.js](https://github.com/dcodeIO/bcrypt.js)**: For hashing user passwords.
* **[dotenv](https://github.com/motdotla/dotenv)**: For managing environment variables.
* **[cors](https://github.com/expressjs/cors)**: For enabling cross-origin resource sharing.

### Frontend (`client`)
* **[React.js](https://reactjs.org/)**: A JavaScript library for building user interfaces.
* **[Vite](https://vitejs.dev/)**: Next-generation frontend tooling for a fast development experience.
* **[React Router](https://reactrouter.com/)**: For client-side routing and navigation.
* **[React Context API](https://reactjs.org/docs/context.html)**: For global state management.
* **[Axios](https://axios-http.com/)**: Promise-based HTTP client for making API requests.
* **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework for rapid UI development.
* **[lucide-react](https://lucide.dev/)**: A clean and simple icon library.

---
