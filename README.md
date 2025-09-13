# 🏡 HouseHunt

**HouseHunt** is a full-stack web application for property rentals and bookings, similar to **Airbnb**.  
Users can list their properties, browse available listings, and make bookings easily.

![React](https://img.shields.io/badge/Frontend-React%2018-blue?logo=react)  
![Node.js](https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-green?logo=node.js)  
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## ⚡ Tech Stack

### 🎨 Frontend
- ⚛️ React 18  
- 🎨 Material-UI (MUI)  
- 🗂️ Redux Toolkit (state management)  
- 🛣️ React Router  
- 🎭 SASS (custom styling)  
- 🧩 React Beautiful DND (drag & drop)  
- 📅 React Date Range (date picker)

### ⚙️ Backend
- 🟢 Node.js with Express  
- 🍃 MongoDB + Mongoose  
- 🔐 JWT Authentication  
- 🖼️ Multer (file uploads)  
- 🌐 CORS (cross-origin requests)

---

## 📂 Project Structure

<details>
<summary>View project tree</summary>

```

project-root/
├── client/                 # Frontend React application
│   ├── public/            # Static files
│   ├── src/              # Source files
│   ├── package.json      # Frontend dependencies
│   └── .env             # Frontend environment variables
│
└── server/                # Backend Node.js application
├── models/           # MongoDB models
├── routes/           # API routes
├── public/           # Uploaded files
├── index.js         # Server entry point
├── package.json     # Backend dependencies
└── .env            # Backend environment variables

````

</details>

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone <repository-url>
cd househunt
````

### 2. Backend setup

```bash
cd server
npm install
```

Create a `.env` file in `/server`:

```
MONGO_URL=mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/HouseHunt?retryWrites=true&w=majority
JWT_SECRET=your_jwt_secret_key_here
PORT=3001
```

### 3. Frontend setup

```bash
cd ../client
npm install
```

Create a `.env` file in `/client`:

```
REACT_APP_API_BASE_URL=http://localhost:3001
```

---

## 🍃 MongoDB Setup

1. Create a free account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
2. Create a new cluster
3. Click **Connect → Connect your application**
4. Copy the connection string
5. Replace `<username>`, `<password>`, and cluster URL in the backend `.env` file

---

## ▶️ Running the Application

### Start backend

```bash
cd server
npm start
```

➡️ Runs on [http://localhost:3001](http://localhost:3001)

### Start frontend

```bash
cd client
npm start
```

➡️ Opens on [http://localhost:3000](http://localhost:3000)

---

## ✨ Features

* 🔑 User authentication (signup/login)
* 🏘️ Property listing creation & management
* 🔎 Property search & filtering
* 📅 Booking system
* 👤 User profiles
* 🖼️ Image upload for properties
* 📱 Responsive design

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch → `git checkout -b feature/AmazingFeature`
3. Commit changes → `git commit -m 'Add AmazingFeature'`
4. Push branch → `git push origin feature/AmazingFeature`
5. Open a Pull Request 🚀

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ *If you found this useful, don’t forget to give the repo a star!*

```

---

This keeps your **logic & structure the same** but makes it:  
- More **visually engaging** (icons + badges).  
- Organized with **collapsible sections**.  
- Easier to scan with **emojis and highlights**.  

Do you also want me to design a **GIF demo preview section** (with a sample placeholder) so recruiters can visually see your app in action?
```
