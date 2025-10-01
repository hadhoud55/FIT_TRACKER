# 🏋️‍♂️ FIT_TRACKER Web Application

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Vue.js](https://img.shields.io/badge/Vue.js-2.6-brightgreen.svg)](https://vuejs.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.7.5-green.svg)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)](https://www.mysql.com/)
[![GitHub stars](https://img.shields.io/github/stars/hadhoud55/FIT_TRACKER?style=social)](https://github.com/hadhoud55/FIT_TRACKER/stargazers)

A **full-stack fitness tracker web application** built with **Spring Boot (backend)** and **Vue.js (frontend)**.  
The app features **JWT authentication**, **role-based access control** (Admin/Coach/User), workout & class management, bookings, reviews, and a shopping cart system for gym products.  
It uses **MySQL** for the database and supports images for users, classes, and products.

---

## ✨ Features

- 🔐 **Authentication & Security**  
  - JWT-based login & registration with Spring Security  
  - Role-based access: Admin / Coach / User  

- 👥 **Roles**  
  - **Admin** → manage users, workouts, classes, products, memberships  
  - **Coach** → manage personal classes and reviews  
  - **User** → browse workouts, classes, products, make bookings, place orders  

- 📦 **Entities**  
  - `User` → account info, roles, profile image (optional)  
  - `Workout` → id, name, description, category  
  - `GymClass` → id, name, schedule, capacity  
  - `GymProduct` → id, name, description, category, price  
  - `Booking` → user bookings for classes  
  - `Order` → order info for products  
  - `Payment` → payment info for orders  
  - `Review` → ratings and feedback for workouts & classes  
  - `Membership` → membership plans for users  

- 💻 **Frontend (Vue.js)**  
  - User authentication (login/register)  
  - Workout & class browsing and booking  
  - Product listing, cart, and checkout  
  - Admin & Coach dashboards for management  
  - Responsive UI with Bootstrap  

- ⚙️ **Backend (Spring Boot)**  
  - RESTful APIs for all entities  
  - MySQL database integration  
  - Pagination, search, and image support  

---

## 🛠️ Tech Stack

**Backend:** Spring Boot, Spring Security, JWT, MySQL  
**Frontend:** Vue.js (Vue CLI), Axios, Bootstrap  

---

## 🚀 Getting Started

### 🔧 Backend Setup

1. Navigate to the backend folder: `Fit_Tracker_Springboot`  
2. Install dependencies and run Spring Boot: `mvn clean install` and `mvn spring-boot:run`  
3. Access the backend APIs at: `http://localhost:8080`  

### 🎨 Frontend Setup

1. Navigate to the frontend folder: `Fit_Tracker_VueJs`  
2. Install dependencies: `npm install`  
3. Run the development server: `npm run serve`  
4. Open the app in your browser: `http://localhost:8081` (or the Vue CLI port)  

---

## 📌 Roadmap

- ✅ JWT authentication  
- ✅ Role-based access (Admin/Coach/User)  
- ✅ Workouts, classes, and products management  
- ✅ Booking system for classes  
- ✅ Orders & payments for products  
- ✅ Reviews & ratings system  
- ✅ Pagination and search for all entities  
- ✅ Image support for users, classes, and products  
- ⏳ Analytics dashboard for Admin/Coach  
- ⏳ Notifications for class bookings  
- ⏳ Multi-language support  
- ⏳ Deployment (Docker / Cloud)  
- ⏳ Testing & code optimization  

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
