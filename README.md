# Customer Relationship Management System (CRM)

A modern, full-stack Customer Relationship Management (CRM) application built using the MERN stack (MongoDB, Express.js, React + Vite, and Node.js)[cite: 3]. Engineered to help organizations manage customer records, enforce role-based access control, track lead lifecycles, and monitor business performance through an interactive analytics dashboard[cite: 3].

> **Notice:** This application is currently undergoing a planned architectural and UI redesign. Project setup guidelines and live access will be made available upon completion of the updated version.

---

## 🛠️ Technology Stack

* **Frontend Engine:** React.js (Vite), JavaScript (ES6+), React Router, Context API (`AuthContext`), Axios[cite: 3, 4, 6]
* **Backend Microservice:** Node.js, Express.js RESTful API Framework[cite: 3, 4]
* **Database Engine:** MongoDB Atlas (Cloud), Mongoose ORM[cite: 3, 4]
* **Authentication & Security:** JSON Web Tokens (`jsonwebtoken`), `bcryptjs` Password Hashing, CORS, `dotenv`[cite: 3, 4, 9]
* **Styling & Design System:** Custom CSS3 with a modern Dark-Mode Card Architecture[cite: 3, 8]

---

## 🌟 Core System Features

* **JWT-Based Authentication & Security:** Secure login workflow backed by encrypted database credentials and session-persistent JSON Web Tokens[cite: 3, 9].
* **Role-Based Access Control (RBAC):**
  * **Admin Role:** Full platform authorization to register employees, manage all customer data, and monitor system-wide analytics[cite: 5].
  * **Employee Role:** Restricted workspace allowing team members to create, update, and manage their assigned customer leads[cite: 5].
* **Customer Lifecycle & Status Tracking:** Complete CRUD (Create, Read, Update, Delete) pipeline tracking customer statuses across `New`, `Contacted`, `In Progress`, and `Closed` stages[cite: 3, 5].
* **Real-Time Analytics Dashboard:** Dynamic statistical counters calculating total customer volume, status distributions, and unassigned leads[cite: 3, 6].
* **Client-Side Pagination Engine:** Lightweight pagination interface restricting viewports to 5 records per page for smooth rendering and usability[cite: 3, 7].
* **Responsive Dark Interface:** Custom-styled dark layout designed for high readability across dashboard statistics, data tables, and customer cards[cite: 3, 8].

---

## 📂 Backend & Frontend Architecture Overview

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
* **Course:** Advance Web Technologies
* **Project Status:** Under Active Redesign
