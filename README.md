# 🛍️ MERN E-Commerce Store

## 📖 Description

This is a modern, full-stack eCommerce web application built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
It features **user, merchant, and admin dashboards**, allowing different users to interact seamlessly within a unified store system.

The project is fully modular, responsive, and optimized for both performance and scalability.

---

## 🚀 Key Features

### 🧑‍💻 User (Customer)
- Browse products, categories, and brands  
- Add products to cart or wishlist  
- Manage profile, addresses, and orders  
- View and track order status  
- Secure login and signup (JWT-based authentication)

### 🏪 Merchant (Seller)
- Manage their brand and products  
- Add, update, or remove items  
- View orders and customer analytics

### 🧑‍💼 Admin
- Control all store components  
- Manage users, brands, products, and orders  
- Monitor store statistics and activities

---

## 🛠️ Tech Stack

| Layer | Technologies Used |
|-------|--------------------|
| **Frontend** | React, Redux, Redux-Thunk, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ODM) |
| **Authentication** | JWT Tokens |
| **Hosting / Deployment** | Vercel, MongoDB Atlas |

---

## 🧩 Features Overview

- 🌐 Full MERN stack integration  
- ⚙️ RESTful API with Express & Node  
- 🧠 Redux for global state management  
- 🎨 Modern UI with React & Tailwind CSS  
- 🔐 Secure authentication and route protection  
- 📦 Product, order, and brand management  
- 📈 Dashboard analytics (admin & merchant)  
- 💬 Wishlist, address, and account management  
- 🧾 Integrated payment-ready structure  

---

## 🖥️ Demo

The application is live on Vercel.  
👉 **[View Demo](https://your-vercel-demo-link.com)**  
(Replace the above link with your live deployment.)

---

## ⚙️ Installation Guide

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/UtkarshJha17/E-Commerce-MERN.git
cd mern-ecommerce
```

### 2️⃣ Install all dependencies:
```bash
npm install
```
This installs both client and server dependencies automatically.

---

## 🔑 Environment Setup

Create a `.env` file inside both the **client** and **server** folders.  
Refer to these templates:

- [Frontend .env Example](client/.env.example)  
- [Backend .env Example](server/.env.example)

Make sure to include:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🧰 Development

Run the app in development mode:
```bash
npm run dev
```
This will start both the frontend (React) and backend (Node) servers concurrently.

---

## 🐳 Docker Support (Optional)

You can also run the app with Docker Compose:
```bash
docker-compose build
docker-compose up
```
Before running, update `MONGO_URI` and `JWT_SECRET` in the `docker-compose.yml` file.

---

## 🌱 Database Seed (Admin User)

To create an admin user for testing:
```bash
npm run seed:db [email@example.com] [password123]
```
This command adds an admin account to your database automatically.

---

## 🚀 Deployment

This project can be deployed easily on **Vercel** for both frontend and backend.

- Set client root directory as `client`  
- Set server root directory as `server`  
- Ensure `vercel.json` files exist in both folders

---

## 🧹 Code Formatting

Add a `.vscode/settings.json` file to enable Prettier formatting in VSCode:

```json
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.jsxSingleQuote": true,
  "prettier.trailingComma": "none",
  "javascript.preferences.quoteStyle": "single"
}
```

---

## 👨‍💻 Author

**Utkarsh Jha**  
📧 [utkarshjha1722@gmail.com](mailto:utkarshjha1722@gmail.com)  
🔗 [GitHub Profile](https://github.com/UtkarshJha17)

---

## ⭐ Acknowledgment

This project was originally inspired by the open-source MERN eCommerce template by **Mohamed Samara**,  
further customized and redesigned with **new UI, dashboard enhancements, and improved frontend styling**.
