# Fresh Mart - Online Store

A full-stack web application for a local grocery/canteen store. Customers can browse items, add to cart, apply coupons, and place orders. Store owners get real-time order notifications via Telegram and manage everything through an admin panel.

## Features

- Product catalog with categories and search
- Shopping cart with quantity management
- Coupon and discount system
- Cash on Delivery and Online Payment support
- Real-time order tracking for customers
- Admin panel for managing items, orders, and revenue
- Telegram notifications for new orders
- PWA support (installable on mobile)
- Voice search

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Notifications:** Telegram Bot API
- **Deployment:** Render

## Project Structure

```
fresh-mart-store/
├── public/
│   ├── index.html        # Customer-facing store
│   ├── admin.html        # Admin login page
│   ├── admin-menu.html   # Manage menu items
│   ├── adm3in.html       # Admin dashboard (orders, revenue)
│   ├── style.css         # Styles
│   ├── sw.js             # Service worker for PWA
│   └── manifest.json     # PWA manifest
├── server.js             # Express server and API routes
├── package.json
├── .env.example          # Environment variable template
└── README.md
```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fresh-mart-store.git
cd fresh-mart-store
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory using `.env.example` as a reference:

```
MONGO_URI=your_mongodb_connection_string
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
TELEGRAM_CHAT_ID=your_telegram_chat_id
ADMIN_PASS=your_admin_password
PORT=3000
```

- **MONGO_URI** — Get this from [MongoDB Atlas](https://www.mongodb.com/atlas)
- **TELEGRAM_BOT_TOKEN** — Create a bot via [@BotFather](https://t.me/botfather) on Telegram
- **TELEGRAM_CHAT_ID** — Your Telegram user/group ID for receiving notifications
- **ADMIN_PASS** — Password for the admin panel

### 4. Run Locally

```bash
npm start
```

Open `http://localhost:3000` in your browser.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/menu` | Get all menu items |
| POST | `/api/order` | Place a new order |
| POST | `/api/verify-coupon` | Validate a coupon code |
| POST | `/api/order-status` | Get status of orders |
| GET | `/api/orders` | Get recent orders (admin) |
| GET | `/api/status` | Get shop open/closed status |
| POST | `/api/admin/login` | Admin authentication |
| POST | `/api/admin/add-item` | Add a menu item |
| POST | `/api/admin/delete-item` | Delete a menu item |
| GET | `/api/admin/revenue` | Get revenue data |

## Deployment

This project is deployed on [Render](https://render.com). Set the environment variables in Render's dashboard under **Environment** settings before deploying.

## License

This project was built for educational purposes.
