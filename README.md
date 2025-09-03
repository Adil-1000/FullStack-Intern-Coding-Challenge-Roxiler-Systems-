# Roxiler Finance Management System

## 📌 Overview

Roxiler Finance Management System is a **full-stack web application** designed to manage user transactions, analyze statistics, and generate insights. It includes role-based access control for **Admin**, **Store Owners**, and **Users**. The system supports creating, editing, and managing transactions seamlessly with real-time analytics.

---

## ✨ Features

* 🔐 **Authentication & Authorization** (JWT-based)
* 👨‍💻 **Role-based Access**

  * **Admin**: Full system access
  * **Store Owner**: Create, edit, and manage transactions
  * **User**: Read-only access
* 💳 **Transaction Management**

  * Create, update, and delete transactions
  * View and filter transaction history
* 📊 **Statistics Dashboard**

  * Visual insights using charts
  * Revenue, transactions, and monthly analysis
* ⚡ **Responsive UI** powered by **Tailwind CSS**
* 🌐 **REST API Integration** with Node.js + Express

---

## 🛠 Tech Stack

**Frontend:** React, TypeScript, Vite, Tailwind CSS
**Backend:** Node.js, Express.js
**Database:** MongoDB (Mongoose ORM)
**Authentication:** JWT-based Auth
**Package Manager:** npm
**Build Tool:** Vite

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/roxiler-finance-app.git
cd roxiler-finance-app/project
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Set Up Environment Variables

Create a `.env` file in the `project/` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4️⃣ Run the Development Server

```bash
# Start backend server
cd server
npm start

# Start frontend
cd ..
npm run dev
```

### 5️⃣ Build for Production

```bash
npm run build
```

---

## 🔑 Demo Login Credentials

Use the following credentials to explore the system:

| Role      | Email                                         | Password |
| --------- | --------------------------------------------- | -------- |
| **Admin** | [admin@roxiler.com](mailto:admin@roxiler.com) | admin123 |
| **Store** | [store@roxiler.com](mailto:store@roxiler.com) | store123 |
| **User**  | [user@roxiler.com](mailto:user@roxiler.com)   | user123  |

---

## 📂 Project Structure

```
project/
├── src/
│   ├── pages/           # React pages (Dashboard, Login, etc.)
│   ├── components/      # Reusable UI components
│   ├── services/        # API calls
│   ├── contexts/        # Auth context provider
│   └── main.tsx         # App entry point
├── server/
│   ├── models/          # Mongoose schemas
│   ├── routes/          # API routes
│   ├── middleware/      # Auth middleware
│   └── index.js         # Express app entry point
├── package.json
├── vite.config.ts
└── tailwind.config.js
```

---

## 📌 Available Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm start        # Start backend server
```

---

## 📡 API Endpoints (Quick Reference)

| Method | Endpoint               | Description          |
| ------ | ---------------------- | -------------------- |
| POST   | /api/auth/login        | Login user           |
| POST   | /api/auth/register     | Register new user    |
| GET    | /api/transactions      | Get all transactions |
| POST   | /api/transactions      | Create transaction   |
| PUT    | /api/transactions/\:id | Update transaction   |
| DELETE | /api/transactions/\:id | Delete transaction   |
| GET    | /api/statistics        | Get dashboard stats  |

---

## 🧑‍💻 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments

Developed by the Roxiler Team. Special thanks to contributors and testers!
