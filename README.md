# eCommerce Platform (MERN Stack)

> A full-featured eCommerce platform built with the **MERN** stack (MongoDB, Express, React, Node).  
> Developed and maintained by **Mrigank Mouli Singh**.

[Live Demo](https://mern-shop-abxs.onrender.com/) • [Report Issues](https://github.com/Mrigank-Mouli-Singh/MERN-eCommerce/issues)

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Demo / Sample Logins](#demo--sample-logins)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Environment Variables](#environment-variables)
  - [Install & Run](#install--run)
  - [Build & Deploy](#build--deploy)
  - [Seed / Destroy Data](#seed--destroy-data)
- [Razorpay & Email (Brevo) Notes](#razorpay--email-brevo-notes)
- [Contributing](#contributing)
- [Project Structure (high level)](#project-structure-high-level)
- [License](#license)
- [Contact](#contact)

---

## About
This project is an end-to-end eCommerce application with user authentication, product browsing, search, pagination, reviews, cart & checkout, order management, and an admin dashboard with product/user/order management. It’s built as a learning & demo project and is production-ready for small deployments.

---

## Features
- Product listing with pagination and keyword search
- Product details, reviews & ratings
- Shopping cart (add / remove / update items)
- Checkout flow with shipping and payment
- Razorpay payment integration
- User profiles with order history
- Admin dashboard:
  - Manage admins
  - Add / edit / delete products
  - Manage users
  - View order details and mark orders as delivered
- Top products carousel
- Database seeder for sample data

---

## Demo / Sample Logins

**Live App:** https://mern-shop-abxs.onrender.com/  
> ⚠️ Render free-tier note: Render may put the app to sleep after ~15 minutes of inactivity. The first request after waking can be slow.

**Admin Dashboard (Live)**
- URL: `https://mern-shop-abxs.onrender.com/admin/login`
- Email: `admin@admin.com`
- Password: `admin123`

**Customer (Live)**
- John Doe — `john@email.com` / `john123`
- Alice Smith — `alice@email.com` / `alice123`

---

## Tech Stack
- Frontend: React (create-react-app)
- Backend: Node.js, Express
- Database: MongoDB (Atlas recommended)
- Payments: Razorpay
- Email: Brevo (SMTP)
- Tools: dotenv, bcrypt, JWT, Mongoose

---

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB Atlas or self-hosted MongoDB
- Razorpay account (Key ID & Key Secret) for payment integration
- Brevo account (SMTP key) for email delivery (order confirmations, password resets)

### Clone the repo
```bash
git clone https://github.com/Mrigank-Mouli-Singh/MERN-eCommerce.git
cd MERN-eCommerce
