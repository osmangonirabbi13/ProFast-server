# 🚛 QuickDrop Courier - Server Side

This is the backend for **QuickDrop Courier**, a parcel delivery web application. It handles user authentication (Firebase Admin SDK), role management, parcel tracking, and database operations using MongoDB.

---
##🔗 Live Site
https://profast-courier.web.app/

---
## Admin Login
link : https://profast-courier.web.app/dashboard
Email : admin@gmail.com	
Password : 123456
---
## Rider Login
link : https://profast-courier.web.app/dashboard
Email : rider@gmail.com
Password : 123456
---
## 📌 About

The backend provides RESTful APIs to manage users, riders, admins, and parcels. It ensures secure access using Firebase Admin SDK and integrates with MongoDB for persistent storage.

---

## 🧩 Key Features

- 🔒 **Firebase Admin Auth Verification**
- 🧑‍💼 **Role-based Access Control** — user, rider, admin
- 📦 **Parcel Management APIs**
- 🚚 **Rider Assignment APIs**
- 📊 **Dashboard Statistics Endpoints**
- 🌍 **CORS and Environment Config Support**
- 🧾 **Order History API for Users and Riders**

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Firebase Admin SDK
- Dotenv

---



##.ENV

MONGODB_URI=your_mongodb_uri
PAYMENT_GATEWAY_KEY=your_PAYMENT_GATEWAY_KEY
FIREBASE_SERVICE_KEY="your_SERVICE_KEY"
.
npm run start
