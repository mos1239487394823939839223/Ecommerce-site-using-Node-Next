<div align="center">

# 🛒 Full-Stack E-Commerce — Node.js + Next.js

**A complete online store built from scratch: an Express/MongoDB REST API and a Next.js storefront with an admin dashboard.**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-0EA5E9?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## 📁 Repository Layout

| Folder | Description |
|---|---|
| [`Ecommerce-Backend-Practice`](./Ecommerce-Backend-Practice) | REST API — Express, MongoDB/Mongoose, JWT auth, validation, image upload |
| [`Ecommerce-Mostafa-Anwer-main`](./Ecommerce-Mostafa-Anwer-main) | Storefront & admin — Next.js 15, TypeScript, Tailwind CSS |

## ✨ Features

**API**
- JWT authentication with role-based access (user / admin)
- CRUD for products, categories, sub-categories and brands
- Filtering, sorting, search and pagination
- Request validation with express-validator and centralised error handling
- Image uploads with Multer

**Storefront**
- Product listing, details, categories and brands
- Cart and checkout flow
- Admin dashboard for managing the catalog

## 🚀 Getting Started

```bash
git clone https://github.com/mos1239487394823939839223/Ecommerce-site-using-Node-Next.git
cd Ecommerce-site-using-Node-Next

# 1) API
cd Ecommerce-Backend-Practice
npm install
npm run start:dev

# 2) Storefront (new terminal)
cd ../Ecommerce-Mostafa-Anwer-main
npm install
npm run dev
```

Backend needs a `config.env` with at least `PORT`, `DB_URI`, `JWT_SECRET` and `JWT_EXPIRES_IN`.

---

<div align="center">

Built by **[Mustafa Anwer Hamed](https://github.com/mos1239487394823939839223)**

</div>
