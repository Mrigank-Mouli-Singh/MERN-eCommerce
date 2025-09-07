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
# Replace `your-username` if using someone else's fork
git clone https://github.com/Mrigank-Mouli-Singh/MERN-eCommerce.git
cd MERN-eCommerce
```

### Env Variables

1. Rename the `.env.example` file to `.env` and add the following environment variables:

```dotenv
NODE_ENV=development
PORT=5000
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
RAZORPAY_KEY_ID=ADD_YOUT_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12 # This will show 12 products per page; you can change it.
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=ADD_YOUR_BREVO_LOGIN
EMAIL_PASS=ADD_YOUR_BREVO_PASSWORD
EMAIL_FROM=ADD_YOUR_BREVO_LOGIN
```

### Install Dependencies

Run the following commands to install dependencies for both the frontend and backend:

```bash
npm install
cd frontend
npm install
```

### Run

To run both the frontend and backend concurrently, use:

```bash
npm run dev
```

To run only the backend:

```bash
npm run server
```

## Build & Deploy

To create a production build for the frontend:

```bash
cd frontend
npm run build
```

## Seed Database

Use the following commands to seed the database with sample users and products, or destroy all data:

```bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

## Sample User Logins

- **Live Admin Dashboard Login:**: [https://mern-shop-abxs.onrender.com/admin/login](https://mern-shop-abxs.onrender.com/admin/login)

  - Email: admin@admin.com
  - Password: admin123

- **Live Customer Logins:**: [https://mern-shop-abxs.onrender.com/login](https://mern-shop-abxs.onrender.com/login)
  - John Doe
    - Email: john@email.com
    - Password: john123
  - Alice Smith
    - Email: alice@email.com
    - Password: alice123

Feel free to explore and customize this eCommerce platform for your specific needs. Happy coding🤩!

# Contributing to the eCommerce Platform Project

We welcome and appreciate contributions from the community to enhance and improve the eCommerce Platform Project. Whether you're a developer, designer, tester, or someone with valuable feedback, your input is valuable. Here's how you can contribute:

## Getting Started

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine:

   ```bash
   git clone https://github.com/your-username/MERN-eCommerce.git
   ```

3. Navigate to the project directory:

   ```bash
   cd MERN-eCommerce
   ```

4. Create a new branch for your contributions:

   ```bash
   git checkout -b feature/your-feature-name
   git checkout -b issues/your-issue-name
   ```

## Making Changes

1. Implement your changes and improvements.

2. Ensure that your changes adhere to the project's coding style and conventions.

3. Test your changes thoroughly to avoid introducing bugs.

4. Update the project documentation if necessary.

## Committing Changes

1. Commit your changes with a descriptive commit message:

   ```bash
   git add .
   git commit -m "Add your descriptive commit message here"
   ```

2. Push your changes to your forked repository:

   ```bash
   git push origin feature/your-feature-name
   git push origin issues/your-issue-name
   ```

## Creating a Pull Request (PR)

1. Visit your forked repository on GitHub.

2. Switch to the branch containing your changes.

3. Click on the "New Pull Request" button.

4. Provide a clear title and description for your pull request, explaining the purpose and scope of your changes.

5. Submit the pull request.

## Code Review

Your contribution will be reviewed by the project maintainer. Be prepared to address any feedback or suggestions to ensure the quality and compatibility of your changes.

## Thank You!

Thank you for considering contributing to the eCommerce Platform Project. Your efforts help make this project better for everyone. If you have any questions or need assistance, feel free to reach out through the issue tracker or discussions.
