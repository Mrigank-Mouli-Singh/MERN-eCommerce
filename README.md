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

- 🛍️ **Shopping Cart** – Add, remove, and manage products easily  
- ⭐ **Product Reviews & Ratings** – Users can review & rate products  
- 🎡 **Top Products Carousel** – Highlights featured items  
- 📄 **Product Pagination** – Browse efficiently  
- 🔎 **Search Functionality** – Search by keywords  
- 👤 **User Profile & Orders** – Track order history  
- 🛠️ **Admin Dashboard** – Manage products, users & orders  
- 🛒 **Product Management** – Create, edit & delete products  
- 👥 **User Management** – Manage user accounts  
- 📦 **Order Management** – Mark orders as delivered  
- 💳 **Razorpay Payments** – Secure checkout  
- 🌱 **Database Seeder** – Preload sample data  

---

## ⚙️ Getting Started  

### 🔑 Prerequisites  
- MongoDB Atlas account  
- Razorpay account for payments  
- Brevo account for email notifications  

---

### 📝 Environment Variables  
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
Backend:

bash
Copy code
npm install
Frontend:

bash
Copy code
cd frontend
npm install
▶️ Running the App
Run backend + frontend together:

bash
Copy code
npm run dev
Backend only:

bash
Copy code
npm run server
Frontend production build:

bash
Copy code
cd frontend
npm run build
🌱 Seed Database
Import sample data:

bash
Copy code
npm run data:import
Clear all data:

bash
Copy code
npm run data:destroy
👥 Sample User Logins
🔑 Admin
Admin Dashboard

Email: admin@admin.com

Password: admin123

🔑 Customers
Customer Login

John Doe → john@email.com / john123

Alice Smith → alice@email.com / alice123

🛠️ Tech Stack
Frontend: React, Redux, React Bootstrap

Backend: Node.js, Express.js

Database: MongoDB (Atlas)

Payments: Razorpay

Email Service: Brevo SMTP

Hosting: Render

🔮 Future Improvements
Add Wishlist & Favorites

Implement Coupon Codes & Discounts

Add Categories & Advanced Filters

Switch frontend to TailwindCSS / Material UI for a modern look

🤝 Contributing
This is my personal project, but contributions and suggestions are always welcome.
If you’d like to collaborate:

Fork the repository

Create a new branch (feature/your-feature)

Commit your changes

Open a Pull Request

📌 Author
👨‍💻 Developed & maintained by Mrigank Mouli Singh
📧 Feel free to reach out with suggestions and improvements.
