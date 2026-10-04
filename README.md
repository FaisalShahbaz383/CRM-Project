# Customer Relationship Management System (CRM)

A modern, full-stack Customer Relationship Management (CRM) application built using the MERN stack (MongoDB, Express.js, React + Vite, and Node.js). Engineered to help organizations manage customer records, enforce role-based access control, track lead lifecycles, and monitor business performance through an interactive analytics dashboard.

> **Notice:** This application is currently undergoing a planned architectural and UI redesign. Project setup guidelines and live access will be made available upon completion of the updated version.

---

## 🛠️️ Technology Stack

* **Frontend Engine:** React.js (Vite), JavaScript (ES6+), React Router, Context API (`AuthContext`), Axios
* **Backend Microservice:** Node.js, Express.js RESTful API Framework
* **Database Engine:** MongoDB Atlas (Cloud), Mongoose ORM
* **Authentication & Security:** JSON Web Tokens (`jsonwebtoken`), `bcryptjs` Password Hashing, CORS, `dotenv`
* **Styling & Design System:** Custom CSS3 with a modern Dark-Mode Card Architecture

---

## 🌟 Core System Features

* **JWT-Based Authentication & Security:** Secure login workflow backed by encrypted database credentials and session-persistent JSON Web Tokens.
* **Role-Based Access Control (RBAC):**
  * **Admin Role:** Full platform authorization to register employees, manage all customer data, and monitor system-wide analytics.
  * **Employee Role:** Restricted workspace allowing team members to create, update, and manage their assigned customer leads.
* **Customer Lifecycle & Status Tracking:** Complete CRUD (Create, Read, Update, Delete) pipeline tracking customer statuses across `New`, `Contacted`, `In Progress`, and `Closed` stages.
* **Real-Time Analytics Dashboard:** Dynamic statistical counters calculating total customer volume, status distributions, and unassigned leads.
* **Client-Side Pagination Engine:** Lightweight pagination interface restricting viewports to 5 records per page for smooth rendering and usability.
* **Responsive Dark Interface:** Custom-styled dark layout designed for high readability across dashboard statistics, data tables, and customer cards.

---

## 📂 Backend & Frontend Architecture Overview

```text
CRM/
├── backend/
│   ├── middleware/        # JWT Authentication & RBAC Authorization
│   ├── models/            # Mongoose Schemas (User & Customer)
│   ├── routes/            # Auth, Customer CRUD, and Dashboard REST Endpoints
│   └── server.js          # Express server entry point
│
└── frontend/
    └── src/
        ├── api/           # Asynchronous Axios HTTP request handlers
        ├── components/    # Navbar & Protected Route wrapper components
        ├── context/       # Global Authentication state provider
        ├── pages/         # Login, Dashboard, and Customer workspace views
        └── styles/        # Global dark theme CSS rules


---

## 👤 Project Information

* **Developer:** Muhammad Faisal
* **Project Status:** Under Active Redesign
