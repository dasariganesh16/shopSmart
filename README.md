# shopSmart 🛍️

**shopSmart** is a full-stack ecommerce platform built using the MERN stack (MongoDB, Express, React, Node.js). It allows buyers to explore products, sellers to manage inventory, and admins to oversee the marketplace ecosystem.

---

## 🌟 Features

- 🔐 Authentication & authorization for buyers, sellers, and admins  
- 📦 Product and category management  
- 🧺 Cart and checkout flow (in progress)  
- 📊 Seller dashboard to manage orders and products  
- 🧭 Admin controls over user roles, listings, and more  
- 🌐 RESTful API with Express  
- 📁 Data modeling with MongoDB/Mongoose  
- 🖥️ Frontend built in React, powered by Redux & Thunk  

---

## 🚀 Getting Started

### Prerequisites

- Node.js v14+  
- MongoDB (local or Atlas cluster)

### Installation

```bash
git clone https://github.com/dasariganesh16/shopSmart.git
cd shopSmart
npm install
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_super_secret_key
🧪 Database Seeding
To create a default admin user, run:
npm run seed:db your-admin@example.com yourPassword123
This script lives in server/utils/seed.js.
npm run dev


shopSmart/
├── client/         # React frontend
│   ├── public/
│   └── src/
├── server/         # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── utils/
├── README.md
├── .gitignore
└── package.json
🛠️ Technologies
Node.js

Express

MongoDB & Mongoose

React

Redux & Redux Thunk

Webpack

🎨 Code Style
To keep your code tidy:

Create a .vscode/ folder

Inside it, make settings.json

Paste the following:

json
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.jsxSingleQuote": true,
  "prettier.trailingComma": "none",
  "javascript.preferences.quoteStyle": "single"
}
Install the Prettier extension in VSCode if needed.

