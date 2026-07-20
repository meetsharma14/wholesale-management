# 🛒 Wholesale Order Management System (WOMS)

A full-stack Wholesale Order Management System built using **React**, **FastAPI**, and **SQLite/PostgreSQL** to help wholesalers efficiently manage products, inventory, retailers, salesmen, orders, invoices, payments, and business reports.

---

## 📌 Overview

The Wholesale Order Management System (WOMS) is a web application that digitizes wholesale business operations by providing role-based dashboards for **Admin**, **Salesman**, and **Retailer**.

The system enables wholesalers to manage products, inventory, retailers, suppliers, salesmen, customer orders, payments, and reports from a single platform.

---

## ✨ Features

### 🔐 Authentication
- JWT Authentication
- Secure Login & Registration
- Role-Based Access Control (RBAC)

### 👤 Admin
- Dashboard
- Product Management
- Category Management
- Supplier Management
- Retailer Management
- Salesman Management
- Order Management
- Payment Tracking
- Business Reports

### 🚚 Salesman
- Dashboard
- Create Orders
- Retailer Visits
- Payment Collection
- Daily Sales Summary

### 🏪 Retailer
- Dashboard
- Browse Product Catalog
- Place Orders
- View Order History
- Payment History
- Outstanding Balance

---

# 🛠 Tech Stack

## Frontend
- React.js
- Vite
- Material UI (MUI)
- React Router DOM
- Axios

## Backend
- FastAPI
- SQLAlchemy
- Pydantic
- JWT Authentication
- Passlib (bcrypt)
- Uvicorn

## Database
- SQLite (Development)
- PostgreSQL (Production)

## Tools
- Git
- GitHub
- VS Code
- Swagger UI
- Postman

---

# 📂 Project Structure

```
Wholesale-Management/
│
├── backend/
│   ├── app/
│   │   ├── core/
│   │   ├── dependencies/
│   │   ├── models/
│   │   ├── routers/
│   │   ├── schemas/
│   │   ├── services/
│   │   ├── database.py
│   │   └── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── layouts/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── theme/
│   │   └── App.jsx
│   └── package.json
│
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/wholesale-management.git
```

```bash
cd wholesale-management
```

---

# Backend Setup

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Backend

```bash
uvicorn app.main:app --reload
```

Backend runs at

```
http://127.0.0.1:8000
```

Swagger Documentation

```
http://127.0.0.1:8000/docs
```

---

# Frontend Setup

Go to frontend folder

```bash
cd frontend
```

Install packages

```bash
npm install
```

Run React App

```bash
npm run dev
```

Frontend runs at

```
http://localhost:5173
```

---

# User Roles

| Role | Permissions |
|------|-------------|
| Admin | Full System Access |
| Salesman | Orders, Retailers, Collections |
| Retailer | Product Catalog, Orders, Payments |

---

# REST APIs

## Authentication
- POST `/auth/register`
- POST `/auth/login`

## Categories
- CRUD APIs

## Products
- CRUD APIs

## Suppliers
- CRUD APIs

## Retailers
- CRUD APIs

## Salesmen
- CRUD APIs

## Orders
- CRUD APIs

## Payments
- CRUD APIs

## Dashboard
- GET `/dashboard/admin`

---

# Screenshots

> Add screenshots of the application here.

- Login Page
- Admin Dashboard
- Product Management
- Orders
- Payments
- Reports

---

# Future Enhancements

- Email Notifications
- SMS Notifications
- Barcode Scanner
- Invoice PDF Generation
- Excel Import/Export
- Sales Analytics
- Multi-Warehouse Support
- GST Reports
- Mobile Application

---

# Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# License

This project is licensed under the MIT License.

---

# Author

**Meet Sharma**

- GitHub: https://github.com/meetsharma14
- LinkedIn: *(Add your LinkedIn URL here)*

---

⭐ If you found this project useful, please consider giving it a star.
