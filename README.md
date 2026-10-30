# Zerodha Clone – Full Stack Trading Platform

A full-stack web application inspired by Zerodha, built to replicate the core features and user interface of an online stock trading platform.

## 🚀 Project Overview

This project is developed to understand and implement the architecture of a full-stack trading platform. It includes a frontend landing page, an interactive trading dashboard, and a backend API built using modern web technologies.

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3
- Bootstrap

**Dashboard**
- React.js
- Material UI
- Chart.js
- Axios

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- REST APIs

## 📁 Project Structure

```text
ZERODHA-CLONE/
│
├── backend/
│   ├── model/
│   ├── schemas/
│   ├── index.js
│   └── package.json
│
├── dashboard/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   └── data/
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   └── landing_page/
│   └── package.json
│
└── README.md
```

## ✨ Key Features

- Responsive landing page inspired by Zerodha.
- Separate trading dashboard interface.
- Watchlist and stock information display.
- Holdings, positions and orders sections.
- Buy action interface.
- Backend REST API structure.
- MongoDB integration using Mongoose.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Shee4300/Zerodha-Clone.git
cd Zerodha-Clone
```

### 2. Install frontend dependencies

```bash
cd frontend
npm install
npm start
```

### 3. Install dashboard dependencies

Open another terminal:

```bash
cd dashboard
npm install
npm start
```

### 4. Configure and run the backend

Open another terminal:

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder and configure:

```env
MONGO_URL=your_mongodb_connection_string
```

Start the backend:

```bash
npm start
```

## 🔐 Environment Variables

Keep sensitive credentials in `.env` files. Never commit database credentials or API secrets to GitHub.

## 🎯 Learning Outcomes

- Understanding full-stack project architecture.
- Building reusable React components.
- Creating REST APIs using Express.js.
- Working with MongoDB and Mongoose.
- Managing frontend and backend integration.
- Organizing a multi-folder development project.

## 👩‍💻 Developer

**Sheetal Shrivastav**

GitHub: [@Shee4300](https://github.com/Shee4300)

---

*This project is developed for educational purposes and is inspired by the Zerodha trading platform. It is not affiliated with or endorsed by Zerodha.*
