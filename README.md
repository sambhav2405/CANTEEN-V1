<div align="center">

<img src="public/logo-removebg-preview (1).png" alt="Fresh Mart Logo" width="120"/>

# 🛒 Fresh Mart — Online Canteen Store

**A modern full-stack web app for ordering food & groceries online.**  
Built with love using Node.js, MongoDB & vanilla JS.

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge)](https://canteen-v1.onrender.com/)
[![Made With](https://img.shields.io/badge/Made%20With-Node.js-339933?style=for-the-badge&logo=node.js)](https://nodejs.org)
[![Database](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb)](https://mongodb.com)
[![Deployed On](https://img.shields.io/badge/Deployed%20On-Render-46E3B7?style=for-the-badge&logo=render)](https://render.com)

---

### 🔗 [https://canteen-v1.onrender.com/](https://canteen-v1.onrender.com/)

</div>

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🛍️ **Product Catalog** | Browse items by category with search & filters |
| 🛒 **Smart Cart** | Add, remove, and manage quantities easily |
| 🎟️ **Coupon System** | Apply discount codes at checkout |
| 💳 **Payment Options** | Cash on Delivery + Online Payment support |
| 📦 **Order Tracking** | Real-time status updates for customers |
| 🔔 **Telegram Alerts** | Instant notifications for new orders |
| 📊 **Admin Dashboard** | Manage items, orders & revenue |
| 📱 **PWA Support** | Installable on mobile like a native app |
| 🎤 **Voice Search** | Search products using your voice |

---

## 🧰 Tech Stack

<div align="center">

| Layer | Technology |
|-------|-----------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas |
| **Notifications** | Telegram Bot API |
| **Hosting** | Render |

</div>

---

## 📁 Project Structure

```
fresh-mart-store/
│
├── 📂 public/
│   ├── index.html          # 🏪 Customer-facing store
│   ├── admin.html          # 🔐 Admin login page
│   ├── admin-menu.html     # 🍽️ Manage menu items
│   ├── adm3in.html         # 📊 Admin dashboard (orders + revenue)
│   ├── style.css           # 🎨 Stylesheet
│   ├── sw.js               # ⚙️ Service Worker (PWA)
│   └── manifest.json       # 📋 PWA manifest
│
├── server.js               # 🚀 Express server & API routes
├── package.json            # 📦 Dependencies
├── .env.example            # 🔑 Environment variable template
└── README.md               # 📖 This file
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/fresh-mart-store.git
cd fresh-mart-store
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
TELEGRAM_CHAT_ID=your_telegram_chat_id
ADMIN_PASS=your_admin_password
PORT=3000
```

> 💡 Use `.env.example` as reference. **Never commit your `.env` file to GitHub!**

| Variable | Where to Get It |
|----------|----------------|
| `MONGO_URI` | [MongoDB Atlas](https://www.mongodb.com/atlas) |
| `TELEGRAM_BOT_TOKEN` | [@BotFather](https://t.me/botfather) on Telegram |
| `TELEGRAM_CHAT_ID` | Your Telegram user/group ID |
| `ADMIN_PASS` | Set your own secure password |

### 4️⃣ Run Locally

```bash
npm start
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 🔐 Admin Panel Access

> **For demo/review purposes only — contact the developer for credentials.**

| Panel | URL |
|-------|-----|
| 🔑 Admin Login | [/admin.html](https://canteen-v1.onrender.com/admin.html) |
| 🍽️ Manage Menu | [/admin-menu.html](https://canteen-v1.onrender.com/admin-menu.html) |
| 📊 Dashboard | Available after login |

---

## 📡 API Endpoints

| Method | Endpoint | Access | Description |
|--------|----------|--------|-------------|
| `GET` | `/api/menu` | Public | Get all menu items |
| `GET` | `/api/status` | Public | Shop open/closed status |
| `POST` | `/api/order` | Public | Place a new order |
| `POST` | `/api/verify-coupon` | Public | Validate a coupon code |
| `POST` | `/api/order-status` | Public | Track order status |
| `GET` | `/api/orders` | Admin | Get recent orders |
| `POST` | `/api/admin/login` | Admin | Admin authentication |
| `POST` | `/api/admin/add-item` | Admin | Add a menu item |
| `POST` | `/api/admin/delete-item` | Admin | Delete a menu item |
| `GET` | `/api/admin/revenue` | Admin | Get revenue analytics |

---

## ☁️ Deployment on Render

1. Push code to GitHub
2. Create a new **Web Service** on [Render](https://render.com)
3. Connect your GitHub repository
4. Go to **Environment → Add Environment Variables** and set all `.env` values
5. Click **Deploy** — you're live! 🎉

---

## 📸 Live Preview

<div align="center">

**👉 Try it now:** [https://canteen-v1.onrender.com/](https://canteen-v1.onrender.com/)

</div>

---

## 📄 License

This project was built for **educational purposes** as part of an academic project.

---

<div align="center">

Made with ❤️ | Powered by Node.js & MongoDB

</div>
