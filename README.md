# 🛒 EasyShop — Full Stack E-Commerce Platform

> A feature-rich MERN stack e-commerce application with role-based access for Buyers, Sellers, and Admins.

![Tech Stack](https://img.shields.io/badge/Stack-MERN-61DAFB?style=for-the-badge)
![Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![Deployed on Vercel](https://img.shields.io/badge/Deployed-Vercel-black?style=for-the-badge&logo=vercel)

---

## 🌐 Live Demo

> 🔗 [Add your deployed Vercel link here]

---

## 📌 Overview

EasyShop is a full-featured e-commerce platform built with the MERN stack. It supports three distinct user roles — each with their own experience and permissions.

| Role | Access |
|------|--------|
| 🛍️ **Buyer** | Browse categories, products, brands & place orders |
| 🏪 **Seller/Merchant** | Manage their own brand and product listings |
| 🔧 **Admin** | Full control over users, products, orders & store settings |

---

## ✨ Features

- 🔐 JWT-based Authentication & Authorization
- 👤 Role-based access control (Buyer / Seller / Admin)
- 🗂️ Product browsing by categories and brands
- 🛒 Cart management with Redux state
- 📦 Order management system
- 🏪 Seller dashboard for brand & product management
- 🛠️ Admin panel for full store control
- 🌐 Third-party API integrations
- 📱 Responsive UI with React

---

## 🛠️ Tech Stack

### Frontend
- **React** — UI components
- **Redux + Redux Thunk** — State management & async actions
- **Webpack + Vite** — Module bundling

### Backend
- **Node.js** — Server environment
- **Express.js** — Middleware, routing
- **Mongoose** — MongoDB schema modeling

### Database
- **MongoDB** — NoSQL database

### DevOps & Tools
- **Vercel** — Deployment (frontend + backend)
- **Postman** — API testing
- **Prettier** — Code formatting

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- MongoDB (local or Atlas)
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/shub6367/Ecommerce.git
cd Ecommerce

# 2. Install dependencies for both client and server
cd client && npm install
cd ../server && npm install
```

### Environment Setup

Create `.env` files in both `client` and `server` directories:

- [Frontend ENV example](./client/.env.example)
- [Backend ENV example](./server/.env.example)

### Run Locally

```bash
# Start both client and server
npm run dev
```

- Client → `http://localhost:3000`
- Server → `http://localhost:5000`
- API prefix → `/api/v1`

### Seed Database

```bash
npm run seed:db admin@example.com yourpassword
```

---

## ☁️ Deployment (Vercel)

Both frontend and backend are deployed on Vercel from the same repository.

- Set root directory as `client` for frontend deployment
- Set root directory as `server` for backend deployment
- Config files: [client/vercel.json](./client/vercel.json) | [server/vercel.json](./server/vercel.json)

---

## 📁 Project Structure

```
Ecommerce/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── ...
├── server/          # Node/Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── ...
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

<p align="center">Built with ❤️ using the MERN Stack</p>
