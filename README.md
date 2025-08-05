# 🎯 Laravel 12 RESTful API Backend

This is a lightweight Laravel 12 backend built with an API-first approach. It exposes secure and structured endpoints (e.g., `/api/all-events`) to serve frontend clients like [Next.js](https://nextjs.org/), mobile apps, or any SPA (React, Vue, etc.).

---

## 📦 Tech Stack

- **Laravel 12** – Backend Framework (API Mode)
- **MySQL** – Relational Database
- **Eloquent ORM** – Data Modeling
- **Sanctum** *(optional)* – API authentication (token-based)
- **CORS Enabled** – For frontend/backend separation
- **JSON API responses** – All endpoints return JSON

---

## 📁 Project Structure
/app <br>
└── Models/ <br>
└── User.php # Event model for the events table <br><br>

/app <br>
└── Http/Controllers/API <br>
└── AuthController.php # Event model for the events table <br><br>

/routes <br>
└── api.php # API-only routes <br><br>

/database <br>
└── migrations/ <br>
└── 202x_xx_xx_create_users_table.php <br><br>

/.env # Environment configuration (DB, app keys, etc.)<br>
composer.json # PHP dependencies