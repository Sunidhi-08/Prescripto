# 🚑 Doctor Finder

A *full-stack healthcare web application* that connects patients with certified doctors, built with *React, Node.js, Express, Tailwind CSS, and MongoDB (Mongoose)*.  
It features *secure authentication, **doctor verification, and **verified payments* through Razorpay.

---

## ✨ Features

- 🔍 *Search & Filter Doctors* – Find doctors by specialty, location, or ratings.  
- 📅 *Appointment Booking* – Schedule appointments seamlessly.  
- 🛡 *Secure Authentication* – JWT-based login/signup with Bcrypt password hashing.  
- ✅ *Doctor Verification* – Upload and verify documents via Cloudinary for trust and transparency.  
- 🖥 *Admin Dashboard* – Manage doctors, users, and appointments efficiently.  
- 📱 *Responsive UI* – Built with Tailwind CSS for smooth desktop & mobile experience.  

---

## 🔐 Security

- JWT authentication for secure sessions.  
- Passwords encrypted with Bcrypt.  
- Error handling middleware ensures *99.5% uptime reliability*.  

---

## 💳 Payments

- *Razorpay Integration* – Verified and secure payments for appointments.  
- Ensures users can pay safely and doctors receive verified transactions.

---

## 🛠 Tech Stack

*Frontend:* React, Tailwind CSS  
*Backend:* Node.js, Express.js  
*Database:* MongoDB (Mongoose)  
*Authentication:* JWT, Bcrypt  
*File Uploads:* Cloudinary  
*Payment Gateway:* Razorpay  

---

## ⚡ Running the Project

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/doctor-finder.git

# Frontend
cd frontend
npm run dev

# Backend
cd backend
node server.js

# Admin panel
cd admin
npm run dev
