"# 📚 EduCore – E-Learning Platform Backend

EduCore is a robust backend system for an E-Learning Platform built using **Node.js**, **Express.js**, **MongoDB**, and **ES6** syntax. It supports a complete educational workflow including user authentication, course management, student enrollment, PayPal payment integration, real-time notifications, and admin dashboard analytics.

---

## 🚀 Features

- 🔐 Role-Based Authentication (JWT)
- 👨‍🏫 Instructor course creation & management
- 🎓 Student course enrollment and tracking
- 💳 Secure PayPal integration for payments
- 🛎️ Notifications system (enrollment, messages, etc.)
- 📈 Admin dashboard with analytics
- 🌐 Internationalization support (multi-language, multi-currency)
- 📩 Email confirmation & PDF ticket receipt
- 📦 Scalable MVC architecture

---

## 📁 Folder Structure
EduCore/
│
├── controllers/ # Business logic
├── models/ # Mongoose schemas
├── routes/ # REST API routes
├── middlewares/ # Auth & error handling
├── utils/ # Helpers (PDF, email, payments)
├── config/ # DB & environment configs
├── uploads/ # File uploads (e.g., thumbnails)
├── .env # Environment variables
├── server.js # Entry point
└── README.md

---

## ⚙️ Tech Stack

- **Backend**: Node.js + Express.js
- **Database**: MongoDB + Mongoose
- **Authentication**: JWT (role-based)
- **Payment Gateway**: PayPal REST SDK
- **PDF Generation**: PDFKit
- **Emailing**: Nodemailer
- **Notifications**: Real-time alerts per user
- **Date Handling**: Day.js
- **File Uploads**: Multer
  
---

## 📦 Installation

bash
git clone https://github.com/CYPRIANCY/E-Learning-Platform-Backend
cd Full Backend
npm install
cp .env.example .env  # Add your MongoDB URI, PayPal keys, etc.
npm run dev

---

- Testing
  
npm run dev 
You can test all REST endpoints via Postman or Thunder Client.

---

- Future Enhancements
Instructor earnings dashboard

WebSocket-based real-time messaging

Video hosting support

Public API marketplace for 3rd-party integrations

Contributing
PRs are welcome! (Open)

Connect
GitHub: https://github.com/CYPRIANCY

LinkedIn: https://www.linkedin.com/akpen-sesugh-cyprian
"

API DOCUMENTATION LINK 
https://documenter.getpostman.com/view/44632922/2sB2x3nDMy
