# 🍽️ Catering Reservation & Ordering System

> A modern web application for managing catering reservations, food menus, and online ordering — built with **React** + **Firebase**.

![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?logo=firebase)

---

## ✨ Features

✅ Seamless **User Registration & Login**  
🍛 Beautifully organized **Menu Listings**  
🛒 Interactive **Cart** and **Order Placement**  
📦 Track all your **My Orders**  
👤 Manage your **User Profile**  
🛠️ **Admin Dashboard** to add/edit products  
☁️ Built on **Firebase Firestore & Authentication**  
💡 Simple & clean UI (Responsive on all devices!)

---


## 🔧 Tech Stack

| 🧠 Frontend       | ⚙️ Backend         | 🧰 Libraries / Tools         |
|------------------|--------------------|------------------------------|
| React (JSX)      | Firebase Firestore | React Router DOM             |
| HTML + CSS       | Firebase Auth      | PostCSS / Tailwind (optional)|
| JavaScript       |                    | Vite / CRA                   |

---

## 📁 Folder Structure

📦 catering-app/
├── 📂 public/                     # Static files
│   └── 📄 index.html              # Main HTML file
├── 📂 src/                        # All source code
│   ├── 📂 components/             # Reusable UI components
│   │   ├── 📂 Auth/               # Login & Register
│   │   │   ├── 🧾 Login.jsx
│   │   │   └── 🧾 Register.jsx
│   │   ├── 📂 Products/           # Product-related views
│   │   │   ├── 🧾 ProductList.jsx
│   │   │   └── 🧾 ProductForm.jsx
│   │   ├── 📂 Orders/             # Cart and Orders
│   │   │   ├── 🧾 Cart.jsx
│   │   │   ├── 🧾 MyOrders.jsx
│   │   │   └── 🧾 PlaceOrder.jsx
│   │   └── 📂 Profile/            # User profile page
│   │       └── 🧾 UserProfile.jsx
│   ├── 📂 pages/                  # Main screens
│   │   ├── 🏠 Home.jsx
│   │   └── 🛠️ AdminDashboard.jsx
│   ├── 📂 context/                # Global state (e.g. Auth)
│   │   └── 🧠 AuthContext.js
│   ├── 📂 firebase/               # Firebase config
│   │   └── 🔥 firebaseConfig.js
│   ├── 📂 utils/                  # Helpers / loggers
│   │   └── 🛠️ logger.js
│   ├── 🎯 App.jsx                 # App entry with routes
│   ├── 🎨 App.css                 # Global styles
│   └── 🚀 index.js                # ReactDOM render entry
├── 📄 .gitignore
├── 📄 package.json
├── 📄 README.md

🧪 Future Improvements
Role-based access control (admin vs user)

Product image uploads with Firebase Storage

Payment gateway integration (e.g., Razorpay)

Order tracking system

Email confirmations

👨‍💻 Author
Debarghya Das
B.Tech CSE Students
GitHub: Debarghya-Das

