# 🚀 D2C Brand Onboarding & Tracking System

## 📌 Overview

This is a full-stack web application built to manage and track D2C (Direct-to-Consumer) brand applications. It allows admins to onboard brands, track their evaluation status, add notes, and monitor pipeline performance.

---

## 🛠️ Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB

### Frontend

* React.js
* Tailwind CSS

---

## ⚙️ Features

### ✅ Brand Management

* Add new brand
* View all brands
* Filter brands by status and category

### 🔄 Status Workflow

Follows strict flow:
SUBMITTED → UNDER_REVIEW → SHORTLISTED → ACCEPTED / REJECTED

Rules:

* No skipping steps
* No going backward
* Final states are ACCEPTED and REJECTED

### 📝 Notes System

* Add notes to each brand
* Helps internal tracking

### 📊 Dashboard Summary

* Total brands
* Submitted count
* Under review count
* Shortlisted count
* Accepted & Rejected count

---

## 📁 Project Structure

brand-project/
│
├── backend/
│   ├── app.js
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│
└── frontend/
├── src/
│   ├── App.js
│   └── index.js

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

git clone https://github.com/YOUR_USERNAME/d2c-brand-tracking-system.git
cd d2c-brand-tracking-system

---

### 2️⃣ Setup Backend

cd backend
npm install

Start server:
node app.js

---

### 3️⃣ Setup Frontend

Open new terminal:

cd frontend
npm install
npm start

---

### 4️⃣ MongoDB Setup

* Install MongoDB locally OR use MongoDB Compass
* Ensure MongoDB is running on:
  mongodb://127.0.0.1:27017

---

## 🔗 API Endpoints

### Create Brand

POST /api/brands

### Get All Brands

GET /api/brands

### Get Single Brand

GET /api/brands/:id

### Update Status

PATCH /api/brands/:id/status

### Add Note

POST /api/brands/:id/notes

### Dashboard Summary

GET /api/brands/summary

---

## 💡 Future Enhancements

* Notes UI in frontend
* Dashboard charts
* Authentication system
* Better UI/UX improvements

---

## 👩‍💻 Author
Lekhya **asivigalla**

---
