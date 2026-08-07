# 🩸 LifeLink – Smart Blood Donation Network

<div align="center">

![MERN](https://img.shields.io/badge/MERN-Stack-success?style=for-the-badge)
![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge\&logo=react)
![NodeJS](https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge\&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-darkgreen?style=for-the-badge\&logo=mongodb)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

### ❤️ Connecting Donors. Saving Lives.

*A modern MERN Stack platform that enables hospitals, blood banks, donors, and recipients to connect instantly during emergencies through real-time notifications, location-based matching, and intelligent donor discovery.*

---

</div>

# 📖 Overview

Every minute matters during a blood emergency.

**LifeLink** is a Smart Blood Donation Network designed to reduce the time required to find compatible blood donors. Instead of relying on manual phone calls or social media posts, LifeLink automatically identifies nearby eligible donors and notifies them instantly.

This project is built using the **MERN Stack** and integrates **Google Maps, GeoSpatial Search, Socket.IO, Firebase Cloud Messaging, Cloudinary, JWT Authentication, and AI-based donor ranking**.

---

# 🚨 Problem Statement

Finding blood donors during emergencies is often slow and unorganized because:

* Lack of centralized donor database
* Manual searching
* No location-based filtering
* Delayed communication
* Difficulty verifying donor eligibility

LifeLink solves these challenges with a smart, automated platform.

---

# 🎯 Objectives

* Find nearby donors in seconds
* Notify eligible donors instantly
* Simplify blood request management
* Manage blood inventory
* Provide secure authentication
* Enable hospitals and blood banks to coordinate efficiently

---

# 👥 User Roles

### 🩸 Donor

* Register/Login
* Update Profile
* Set Blood Group
* Live Availability Status
* Donation History
* Receive Emergency Requests
* Accept/Reject Requests

---

### 🧑‍🤝‍🧑 Recipient

* Search Donors
* Request Blood
* Track Request Status
* View Nearby Donors

---

### 🏥 Hospital

* Emergency Blood Requests
* Manage Patients
* Track Active Requests
* View Nearby Donors

---

### 🏦 Blood Bank

* Blood Inventory
* Stock Management
* Donation Scheduling

---

### 👨‍💻 Admin

* Dashboard Analytics
* User Verification
* Hospital Verification
* Blood Bank Approval
* Reports & Statistics

---

# ✨ Features

## Authentication

* JWT Authentication
* Role Based Authorization
* Secure Password Hashing
* Forgot Password
* Email Verification

---

## Smart Donor Search

* Nearby Donor Detection
* GeoSpatial Search
* Google Maps Integration
* Blood Group Compatibility
* Distance Filtering

---

## Emergency Blood Requests

* Create Emergency Request
* Accept / Reject Request
* Live Status Tracking
* Request History

---

## Real-Time Communication

* Socket.IO Notifications
* Live Request Updates
* Instant Alerts

---

## Notifications

* Email Notifications
* Push Notifications (Firebase)
* In-App Notifications

---

## Blood Donation

* Donation History
* Eligibility Checker
* Next Donation Reminder
* Digital Donation Certificate

---

## Admin Dashboard

* Total Users
* Total Donors
* Active Requests
* Blood Inventory
* Analytics Charts

---

# 🛠 Tech Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* Redux Toolkit
* React Router
* Axios
* Framer Motion

---

## Backend

* Node.js
* Express.js

---

## Database

* MongoDB Atlas
* Mongoose

---

## Authentication

* JWT
* bcryptjs

---

## Maps & Location

* Google Maps API
* Geolocation API
* MongoDB GeoSpatial Queries

---

## Real-Time

* Socket.IO

---

## Notifications

* Firebase Cloud Messaging
* Nodemailer

---

## Media Storage

* Cloudinary
* Multer

---

## Deployment

* Vercel (Frontend)
* Render (Backend)
* MongoDB Atlas

---

# 📂 Project Structure

```text
LifeLink/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── validations/
│   └── server.js
│
├── docs/
│
├── README.md
│
└── .gitignore
```

---

# 🗄 Database Collections

* Users
* Donors
* Hospitals
* BloodBanks
* BloodRequests
* Donations
* Notifications
* Inventory

---

# 🔄 Project Workflow

```text
Recipient/Hospital
        │
        ▼
Create Blood Request
        │
        ▼
Blood Group Matching
        │
        ▼
Nearby Donor Search
        │
        ▼
AI Donor Ranking
        │
        ▼
Socket.IO Notifications
        │
        ▼
Donor Accepts Request
        │
        ▼
Hospital Receives Confirmation
```

---

# 🔒 Security Features

* JWT Authentication
* Password Encryption
* Protected Routes
* Input Validation
* Rate Limiting
* CORS
* Helmet
* Environment Variables

---

# 🚀 Future Enhancements

* AI-based Donor Recommendation
* QR Code Verification
* Aadhaar Verification
* Voice Assistant
* Ambulance Integration
* Multi-language Support
* Progressive Web App (PWA)

---

# 📸 Screenshots

> Add project screenshots here after completing the UI.

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Jyoti-coder-1004/lifelink-smart-blood-donation.git
```

## Frontend

```bash
cd client
npm install
npm run dev
```

## Backend

```bash
cd server
npm install
npm run dev
```

---

# 👨‍💻 Developed By

**Jyoti Singh**

B.Tech CSE Student | MERN Stack Developer

---

# ⭐ Support

If you like this project, don't forget to **Star ⭐ the repository** and contribute to making blood donation faster and smarter.

---

## ❤️ "One Donation Can Save Multiple Lives."
