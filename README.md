<div align="center">

<img src="public/logo-removebg-preview (1).png" width="110"/>

# 🛒 Fresh Mart — Online Canteen Store

> *Order karo, ghar baitho, khao mast!* 🍔🥗🧃

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Site-Visit%20Now-brightgreen?style=for-the-badge)](https://canteen-v1.onrender.com/)
[![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Express](https://img.shields.io/badge/Express.js-REST%20API-000000?style=for-the-badge&logo=express)](https://expressjs.com)
[![Render](https://img.shields.io/badge/Deployed%20on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)
[![PWA](https://img.shields.io/badge/PWA-Enabled-5A0FC8?style=for-the-badge&logo=pwa)](https://canteen-v1.onrender.com/)
[![Telegram](https://img.shields.io/badge/Telegram-Notifications-26A5E4?style=for-the-badge&logo=telegram)](https://telegram.org)
[![License](https://img.shields.io/badge/License-Educational-orange?style=for-the-badge)](#)

---

## 🔗 [https://canteen-v1.onrender.com/](https://canteen-v1.onrender.com/)

</div>

---

## ✨ Features at a Glance

```
🛍️  Product Catalog     →  Browse items by category, search & filter
🛒  Smart Cart          →  Add, update, remove items with ease
🎟️  Coupon System       →  Apply discount codes at checkout
💳  Payment Options     →  Cash on Delivery + Online Payment
📦  Order Tracking      →  Real-time status updates for customers
🔔  Telegram Alerts     →  Instant notifications on new orders
📊  Admin Dashboard     →  Manage items, orders & revenue analytics
📱  PWA Support         →  Install on mobile like a native app
🎤  Voice Search        →  Search products hands-free
```

---

## 🧰 Tech Stack

<div align="center">

| Layer | Technology |
|:------|:-----------|
| 🎨 **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| ⚙️ **Backend** | Node.js + Express.js |
| 🗄️ **Database** | MongoDB Atlas |
| 🔔 **Notifications** | Telegram Bot API |
| ☁️ **Hosting** | Render |

</div>

---

## 📁 Project Structure

```
fresh-mart-store/
│
├── 📂 public/
│   ├── 🏪 index.html          →  Customer-facing store
│   ├── 🔐 admin.html          →  Admin login page
│   ├── 🍽️  admin-menu.html     →  Manage menu items
│   ├── 📊 adm3in.html         →  Admin dashboard (orders + revenue)
│   ├── 🎨 style.css           →  Stylesheet
│   ├── ⚙️  sw.js               →  Service Worker (PWA)
│   └── 📋 manifest.json       →  PWA manifest
│
├── 🚀 server.js               →  Express server & all API routes
├── 📦 package.json            →  Project dependencies
├── 🔑 .env.example            →  Environment variable template
└── 📖 README.md               →  You're reading this!
```

---

## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/fresh-mart-store.git
cd fresh-mart-store
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file in root directory:

```env
MONGO_URI=your_mongodb_connection_string
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
TELEGRAM_CHAT_ID=your_telegram_chat_id
ADMIN_PASS=your_admin_password
PORT=3000
```

| Variable | Where to Get |
|:---------|:------------|
| `MONGO_URI` | [MongoDB Atlas](https://www.mongodb.com/atlas) |
| `TELEGRAM_BOT_TOKEN` | [@BotFather](https://t.me/botfather) on Telegram |
| `TELEGRAM_CHAT_ID` | Your Telegram user/group ID |
| `ADMIN_PASS` | Set your own secure password |

> ⚠️ **Never commit your `.env` file!** It's already in `.gitignore` ✅

### 4️⃣ Run the App
```bash
npm start
```
Open **[http://localhost:3000](http://localhost:3000)** 🎉

---

## 🔐 Admin Panel — Demo Access

> Use the credentials below to explore the admin panel on the live site.

<div align="center">

| Field | Value |
|:-----:|:-----:|
| 🌐 **Admin URL** | [canteen-v1.onrender.com/admin.html](https://canteen-v1.onrender.com/admin.html) |
| 👤 **Username** | `admin` |
| 🔑 **Password** | `Jain@245` |

</div>

> 📌 **Admin Panels:**
> - 🔐 Login → [/admin.html](https://canteen-v1.onrender.com/admin.html)
> - 🍽️ Manage Menu → [/admin-menu.html](https://canteen-v1.onrender.com/admin-menu.html)
> - 📊 Dashboard → Accessible after login

---

## 📡 API Endpoints

| Method | Endpoint | Access | Description |
|:------:|:---------|:------:|:------------|
| `GET` | `/api/menu` | 🌍 Public | Fetch all menu items |
| `GET` | `/api/status` | 🌍 Public | Shop open/closed status |
| `POST` | `/api/order` | 🌍 Public | Place a new order |
| `POST` | `/api/verify-coupon` | 🌍 Public | Validate a coupon code |
| `POST` | `/api/order-status` | 🌍 Public | Track order by ID |
| `GET` | `/api/orders` | 🔐 Admin | Get all recent orders |
| `POST` | `/api/admin/login` | 🔐 Admin | Admin authentication |
| `POST` | `/api/admin/add-item` | 🔐 Admin | Add a new menu item |
| `POST` | `/api/admin/delete-item` | 🔐 Admin | Remove a menu item |
| `GET` | `/api/admin/revenue` | 🔐 Admin | Revenue analytics |

---

## ☁️ Deploying on Render

1. Push your code to **GitHub**
2. Go to [Render.com](https://render.com) → **New Web Service**
3. Connect your GitHub repo
4. Under **Environment**, add all `.env` variables
5. Hit **Deploy** — you're live! 🚀

---

## 📸 Live Preview

<div align="center">

| 🏪 Customer Store | 🔐 Admin Panel |
|:-----------------:|:--------------:|
| [Open Store](https://canteen-v1.onrender.com/) | [Open Admin](https://canteen-v1.onrender.com/admin.html) |

**✨ Try the live app → [https://canteen-v1.onrender.com/](https://canteen-v1.onrender.com/)**

</div>

---

## 📄 License

This project was built for **educational purposes** as part of an academic submission.

---

<div align="center">

Made with ❤️ &nbsp;|&nbsp; Node.js + MongoDB + Express &nbsp;|&nbsp; Deployed on Render

⭐ *Star this repo if you found it useful!*

</div>
