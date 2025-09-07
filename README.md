# 🛒 MERN eCommerce Platform  

This is my **full-stack eCommerce platform** built using the **MERN stack** (MongoDB, Express.js, React, Node.js).  
It is a complete online shopping application with essential and advanced features, designed and customized by **Mrigank Mouli Singh**.  

---

## 🚀 Live Demo  
🔗 [Click here to view the live app](https://mern-shop-abxs.onrender.com/)  

⚠️ Render’s free tier automatically shuts down after 15 minutes of inactivity.  
The first request after reactivation may take longer, but subsequent requests will be faster.  

---

## ✨ Features  

🛍️ Shopping Cart – Add, remove, and manage products easily
⭐ Product Reviews & Ratings – Users can review & rate products
🎡 Top Products Carousel – Highlights featured items
📄 Product Pagination – Browse efficiently
🔎 Search Functionality – Search by keywords
👤 User Profile & Orders – Track order history
🛠️ Admin Dashboard – Manage products, users & orders
🛒 Product Management – Create, edit & delete products
👥 User Management – Manage user accounts
📦 Order Management – Mark orders as delivered
💳 Razorpay Payments – Secure checkout
🌱 Database Seeder – Preload sample data

yaml
Copy code

---

## ⚙️ Getting Started  

### 🔑 Prerequisites  
MongoDB Atlas account

Razorpay account for payments

Brevo account for email notifications

makefile
Copy code

---

### 📑 Environment Variables  

Create a `.env` file in the root folder and add:  

```env
NODE_ENV=development
PORT=5000
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
RAZORPAY_KEY_ID=ADD_YOUR_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=ADD_YOUR_BREVO_LOGIN
EMAIL_PASS=ADD_YOUR_BREVO_PASSWORD
EMAIL_FROM=ADD_YOUR_BREVO_LOGIN
📦 Installation
bash
Copy code
# Backend installation
npm install

# Frontend installation
cd frontend
npm install
▶️ Running the App
bash
Copy code
# Run backend + frontend together
npm run dev

# Run backend only
npm run server

# Build frontend production version
cd frontend
npm run build
🌱 Seed Database
kotlin
Copy code
# Import sample data
npm run data:import

# Destroy all data
npm run data:destroy
👥 Sample User Logins
pgsql
Copy code
# Admin
URL: /admin/login
Email: admin@admin.com
Password: admin123
graphql
Copy code
# Customers
URL: /login

John Doe → john@email.com / john123  
Alice Smith → alice@email.com / alice123  
🛠️ Tech Stack
yaml
Copy code
Frontend: React, Redux, React Bootstrap  
Backend: Node.js, Express.js  
Database: MongoDB (Atlas)  
Payments: Razorpay  
Email Service: Brevo SMTP  
Hosting: Render  
🔮 Future Improvements
diff
Copy code
- Add Wishlist & Favorites  
- Implement Coupon Codes & Discounts  
- Add Categories & Advanced Filters  
- Switch frontend to TailwindCSS / Material UI for a modern look  
🤝 Contributing
markdown
Copy code
1. Fork the repository  
2. Create a new branch (feature/your-feature)  
3. Commit your changes  
4. Open a Pull Request  
📌 Author
👨‍💻 Developed & maintained by Mrigank Mouli Singh
📧 Feel free to reach out with suggestions and improvements.
