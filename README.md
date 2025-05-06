# FullStack Intern Coding Challenge

## 💡 Overview
A web app to manage stores, users, and ratings, with roles including System Admin, Store Owner, and Normal User.

## 🛠️ Tech Stack
- **Frontend:** ReactJS
- **Backend:** ExpressJS / NestJS / Loopback
- **Database:** PostgreSQL / MySQL

## 🔐 User Roles and Functionalities
### 👨‍💼 System Administrator
- Add stores and users
- View analytics and lists with filters

### 🙍 Normal User
- Register, login, submit & update ratings

### 🏪 Store Owner
- Login, view store rating, and user feedback

## ✅ Form Validations
- Name: 20–60 characters
- Email: Valid format
- Password: 8–16 chars, one uppercase, one special
- Address: Max 400 chars

## 🧱 Features
- Role-based login
- Ratings (1–5)
- Dashboard with sorting and search
- Password updates

## 📁 Folder Structure
- `/frontend`: ReactJS app
- `/backend`: API & Auth
- `/database`: Schema + seed files

## 🚀 Setup Instructions

### Backend
```bash
cd backend
npm install
npm start
