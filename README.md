# RetailMall - Enterprise E-Commerce Platform

A high-performance, production-ready, full-stack e-commerce solution features a dual-frontend architecture (Customer Storefront + Admin Dashboard), multi-language localization (English/Urdu with native RTL support), and a robust Node.js/Express backend powered by MySQL.

---

## 🏗️ Master Project Directory Structure

Create this exact directory layout in your VS Code workspace before setting up the files:

```text
RetailMall/
│
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── middleware/
│   │   └── auth.js
│   ├── controllers/
│   │   ├── authController.js
│   │   └── productController.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── productRoutes.js
│   ├── models/
│   │   └── schemas.sql
│   ├── .env.example
│   ├── package.json
│   └── server.js
│
├── frontend/ (To be generated)
├── admin-panel/ (To be generated)
└── README.md
