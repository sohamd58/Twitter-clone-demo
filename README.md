
# 🐦 Full-Stack Twitter Clone (MERN + Tailwind)

A fully functional Twitter-like social media platform built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project implements core social features including user authentication, posting, notifications, and a responsive timeline – ideal for showcasing real-world full-stack development skills.

---

## 📌 Project Highlights

- 🧩 **Full-Stack Integration**: End-to-end architecture from database to UI
- 🔐 **JWT Authentication**: Secure login and protected user routes
- 📝 **Post System**: Create, read, and interact with tweets
- 🔔 **Notifications**: Real-time alerts for actions like follows or likes
- 👤 **User Profiles**: Dynamic profile view with user-specific data
- 💅 **Modern UI**: Clean, responsive design using Tailwind CSS
- 💼 **Portfolio-Ready**: Clean code, scalable structure, easy to extend

---

## 📁 Folder Structure

```text
Twitter-clone-demo-main/
├── backend/                  # Node/Express backend
│   ├── controllers/          # Route logic (auth, posts, users, notifications)
│   ├── db/                   # MongoDB connection setup
│   ├── lib/utils/            # Token generation utility
│   ├── middleware/           # Auth middleware (JWT verification)
│   ├── models/               # Mongoose schemas
│   ├── routes/               # REST API routes
│   └── server.js             # Entry point for backend server
│
├── frontend/                 # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Pages like Home, Login, Profile
│   │   ├── App.js
│   │   └── index.js
│
├── .env-sample               # Sample environment file
├── .gitignore
├── README.md
├── package.json
├── package-lock.json
````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sohamd58/Twitter-clone-demo.git
cd Twitter-clone-demo
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Environment Variables

Create a `.env` file in the `backend/` directory with:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the Application

Use separate terminals for backend and frontend:

```bash
# Terminal 1: Backend
cd backend
npm run dev
```

```bash
# Terminal 2: Frontend
cd frontend
npm start
```

---

## 🧩 Tech Stack

* **Frontend**: React, Tailwind CSS, React Router
* **Backend**: Express.js, MongoDB, Node.js, Mongoose
* **Authentication**: JWT + bcrypt
* **Utilities**: dotenv, axios, nodemon

---

## 📣 Contributing

Contributions are welcome! If you spot bugs or have suggestions, feel free to open issues or submit a PR.

---

⭐ **Star this repo** to support the project!
📫 **Connect** on [LinkedIn](https://www.linkedin.com/in/soham-d1758) or GitHub!

---

