# 🌍 WanderLust – Hotel Booking Web App

**WanderLust** is a full-stack web application inspired by Airbnb, designed for hotel listing and booking. This project demonstrates CRUD operations, RESTful routing, and dynamic content rendering with a clean and responsive UI.

---

## ✅ Current Status – Phase 1 Completed

The current version includes the foundational features and backend setup. Future phases will introduce advanced functionality.

### 🔹 Phase 1 Features (Implemented):
- Built RESTful APIs using **Node.js** and **Express.js**
- Integrated **MongoDB** (via Mongoose) for storing hotel listings
- Developed full **CRUD operations** for listings
- Rendered dynamic pages using **EJS**
- Designed a responsive UI with **Bootstrap**
- Created separate detail pages for each hotel

> 💡 All code currently pushed to this repository is for **Phase 1 only**.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB + Mongoose
- **Templating Engine:** EJS
- **Frontend:** HTML, CSS, Bootstrap
- **Version Control:** Git, GitHub

---

## 🔮 Upcoming Phases (Coming Soon)

These features are planned and will be added in future updates:

- 💳 Payment Gateway Integration (e.g., Razorpay/Stripe)
- ⭐ Reviews & Ratings
- 🔍 Search & Filter by location, price, rating, etc.
- 🖼️ Image Uploads (Cloudinary)
- 🔐 Authentication & Authorization
- 📍 Map Integration (Google Maps API)

---


wanderlust/
│
├── app.js # Main application file
├── package.json # Project metadata and dependencies
├── package-lock.json # Dependency lock file
│
├── init/
│ ├── data.js # Initial data for seeding
│ └── index.js # Entry for data initialization
│
├── models/
│ └── listing.js # Mongoose schema for hotel listings
│
├── public/
│ └── css/
│ └── style.css # Custom styles
│
├── views/
│ ├── includes/ # Reusable partials (header/footer)
│ │ ├── footer.ejs
│ │ └── navbar.ejs
│ │
│ ├── layouts/ # Layout boilerplate for consistent UI
│ │ └── boilerplate.ejs
│ │
│ └── listings/ # Views for CRUD operations
│ ├── index.ejs # Homepage listing view
│ ├── new.ejs # Form to add new listing
│ ├── show.ejs # Detail page of a listing
│ └── edit.ejs # Form to edit existing listing
│
└── node_modules/ # Node.js dependencies (auto-generated)



